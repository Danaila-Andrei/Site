This is a project I worked on during university. It is a website featuring multiple cooking recipes. Each recipe has a dedicated page that includes an image of the recipe, a section for the ingredients, and the preparation method. For the preparation method, we implemented an unordered list with checkboxes that allow users to check off the steps they've completed while scrolling.

To manipulate the data on the website, I used querySelector from the DOM API in JavaScript. For example, I dynamically updated elements like the ingredients list and the preparation steps directly in the HTML using DOM queries.
The website also includes a comment section where users can post comments, which are saved in a Firebase database. The comments from Firebase are fetched from the real-time database and displayed on the homepage.

The site also features a login page that allows users to create an account by entering their details, which are saved in Firebase as well. For signing in, the application checks the database to verify whether the username and password exist, and then redirects the user to the homepage if the credentials are valid.
Also I used Html and css for style and make all happend.
