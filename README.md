# JSON-Placeholder-User-Posts-App
This web application provides a user-friendly interface to interact with the JSONPlaceholder API, displaying user information alongside their posts. The project utilizes HTML, CSS, and JavaScript to create a seamless user experience. The JavaScript code has been enhanced with promises for better readability and asynchronous operations.

The project serves as a web page that dynamically fetches user and post data from the JSONPlaceholder API. Users are presented with a list of individuals, each represented as a clickable card. Upon selecting a user, the associated posts are displayed on the right side of the page.


Users Section (#users)
Displays a list of users in a visually appealing card format.
Each user card is clickable, triggering the display of their associated posts.
The selected user is visually highlighted with an orange border.
Posts Section (#posts)
Shows the posts of the selected user.
Each post is presented in a card with a title and body.

## Features
Asynchronous Data Fetching:

Utilizes the fetch API with promises to asynchronously retrieve user and post data from the JSONPlaceholder API.
Dynamic User Interaction:

Users can click on a user card to view their associated posts.
Visual indication of the selected user enhances the user experience.

**getUsers Function**
Fetches user data from the JSONPlaceholder API using the fetch API.
Returns a promise that resolves when the data is successfully fetched.
Rejects the promise if there is an error during the API request.
**getPosts Function**
Fetches post data for a specific user ID using the fetch API.
Dynamically creates HTML elements for each post and appends them to the #posts container.
Clears the existing posts before displaying the new ones.
**userClicked Function**
Invoked when a user card is clicked.
Calls the getPosts function to fetch and display posts for the selected user.
Updates the visual styling to indicate the selected user.
