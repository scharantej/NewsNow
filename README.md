## Flask Application for Displaying Recent News Articles

### HTML Files
- **home.html**: This is the home page of the application, which will display a list of recent news articles. It should include elements for displaying the article titles, publish dates, and a link to the full article.

### Routes
- **\**: This route is associated with the home page and will display the list of recent news articles by rendering the `home.html` file.
- **\article\<id\>**: This route will take an article ID and display the full article associated with that ID. It should retrieve the article from a database or external source and render it on a separate page.