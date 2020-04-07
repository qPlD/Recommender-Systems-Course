# Recommender-Systems-Course

## Introduction
The aim of this exercise is to build and evaluate a recommender system on user data.
</br>The RS (**Spotlight**) will be evaluated using both implicit and explicit data.

The exercise contains four main tasks:
1. Instantiate and evaluate non-personalised recommendation algorithms, based on explicit rating
data.
2. Instantiate and evaluate a rating-prediction recommendation algorithm, based on both explicit
and implicit rating data.
3. Instantiate and evaluate a recommendation algorithm based on implicit user interaction data.
4. Combine various recommender systems from the above tasks, using a fusion of their
recommendation rankings.

## Dataset
This exercise uses a dataset of interactions and ratings from Goodreads. Goodreads is a
website allowing users to be recommended books to read. Users can "shelf" books (implicit interaction)
and can also (explicitly) rate books. The following sub-types of datasets are available:
* *to_read.csv*: Users have indicated that they wish to or have read books (e.g. placing on a
shelf) - implicit data.
* *ratings.csv*: Users have rated books (1-5 stars) - explicit data.
* *test.csv*: Test set of users who placed books onto shelves – this is your test set.
Finally, we also provide metadata about each book:
* *books.csv*: information about each book (e.g. title, authors, rating distribution).

## Exercise Goal
The aim of this exercise is to make an effective recommender system to predict books that users should
place next on their shelf. The provided template Colab notebook should be used. In this notebook, we
have already separated the implicit data into training and test datasets. We have further split the implicit
training data (80%/20%) to make a validation set. The template notebook loads all datasets as Spotlight
Interaction objects, thereby handling the mapping of user_ids ⟷ uids, and book_ids ⟷ iids.
