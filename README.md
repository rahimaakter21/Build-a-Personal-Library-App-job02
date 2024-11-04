### Job 2: Build a Personal Library App

## Description: Develop an Android app to manage a personal library of books using Room Database to store book details.Book Data Model:Define an entity class for a Book with fields for:

    id (primary key, auto-generated)
    title (String, required)
    author (String, required)
    pages (int, required)
    isRead (Boolean, default to false)

## CRUD Operations:

    Create: Enable users to add new books to their library by entering the title, author, and number of pages.
    Read: Show the list of books in a RecyclerView, grouped by read and unread status.
    Update: Allow users to edit a book’s details, such as title, author, and page count.
    Delete: Let users delete books individually by swiping left or right on each item in the RecyclerView.

    Mark as Read/Unread:Include a toggle button or checkbox to mark books as "Read." When marked, isRead is updated in the database, and the item moves to the "Read" section in the list.Search and Sort Options:
    Implement a search feature to find books by title or author.
    Add sorting options to sort books alphabetically by title, by author name, or by number of pages.

## UI Requirements:

    Use Android Jetpack components like ViewModel, LiveData, and Data Binding.
    Display the list of books in a RecyclerView, organized by read status.
    Follow MVVM architecture for separation of concerns between UI and data.
