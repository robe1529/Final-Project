# Final-Project

1. Project Type: Plan C
2. Group Members Name: Kyle Roberts
3. Link to live Application: https://calm-mountain-14300.herokuapp.com
4. Link to Github Code Repository: https://github.com/robe1529/Final-Project/tree/deploy
5. List of Technologies/API's Used: Flask, WTForms, etc.
6. Detailed Description of the project: NA
7. List of Controllers and their short description:
      - before_request
          Updates user last login date/time if current user is registered
      - index
          Handles adding new blog post to database, rendering the page with the user's posts, and taking care of redirect bugs
      - login
          If current user isn't logged in, verifies login information entered in form and redirects to user's home page if verified
      - logout
          Logs user out and redirects to main page
      - register
          Upon form validation, add new user to database and redirect them to their new homepage
      - user
      - edit_profile
      - follow
      - unfollow
      - explore
8. List of Views and their short description:
      - _post
          Handles displaying a user's username and avatar along with their post
      - 404
          Provides link back to index upon error
      - 500
          Same as 404
      - base
          Provides general layout of page titling and navbar display/updating.
      - edit_profile
          Login-required page for allowing a user to edit their username and personal description
      - index
          Login-required page. This is the main page when logged in that displays the most recent blog updates from other users and provides an entry box to submit a new post.
      - login
          Sign-in page for returning users. Provides the option to remember the user on subsequent visits and has registration link for new users.
      - register
          Page for signing-up to be a user. Adds registration form to base.html
      - user
          Login-required page for viewing a user's profile. Includes their personal bio, last login date/time, list of followers, and list of recent posts.
9. List of Tables, their Structure and short description

10. References/Resources: https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world
