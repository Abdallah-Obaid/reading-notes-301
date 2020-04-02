# Read 05 ~ Heroku Deployment
> By Abdallah obaid

**NAME**     | **URL**
------------ | -------------
Home         | [Home](https://abdallah-obaid.github.io/reading-notes-301/).
 Read 01     | [SMACSS and Responsive Web Design](https://abdallah-obaid.github.io/reading-notes-301/class-01).
 Read 02     | [jQuery, Events, and The DOM](https://abdallah-obaid.github.io/reading-notes-301/class-02).
 Read 03     | [Flexbox and Templating](https://abdallah-obaid.github.io/reading-notes-301/class-03).
 Read 04     | [Responsive Web Design and Regular Expressions](https://abdallah-obaid.github.io/reading-notes-301/class-04).
 Read 05     | [Heroku Deployment](https://abdallah-obaid.github.io/reading-notes-301/class-05).
 Read 06     | [Node, Express, and APIs](https://abdallah-obaid.github.io/reading-notes-301/class-06).
 Read 07     | [APIs continued](https://abdallah-obaid.github.io/reading-notes-301/class-07).
 Read 08     | [SQL](https://abdallah-obaid.github.io/reading-notes-301/class-08).
 Read 09     | [Refactoring](https://abdallah-obaid.github.io/reading-notes-301/class-09).
 Read 10     | [The Call Stack and Debugging](https://abdallah-obaid.github.io/reading-notes-301/class-10).
 Read 11     | [EJS](https://abdallah-obaid.github.io/reading-notes-301/class-11).
 Read 12     | [Components](https://abdallah-obaid.github.io/reading-notes-301/class-12).
 Read 13     | [Update/Delete](https://abdallah-obaid.github.io/reading-notes-301/class-13).
 Read 14a    | [DB Normalization](https://abdallah-obaid.github.io/reading-notes-301/class-14a).
 Read 14b    | [Project Ideas & APIs](https://abdallah-obaid.github.io/reading-notes-301/class-14b).
 Read 15     | [Diversity and Inclusion](https://abdallah-obaid.github.io/reading-notes-301/class-15).

 
----------------------------------
# Heroku Deployment:-
----------------------------------
 * We use the heroku login command to log in to the Heroku CLI.
 * The authentication is required for both the heroku and git commands to work correctly.
 * Heroku need the git, node.js and npm to work.
 * heroku create: will Create an app on Heroku, which prepares Heroku to receive your source code.
 * git push heroku master: will push/deploy my work to the heroku server.
 * heroku ps:scale web=1: to Ensure that at least one instance of the app is running.
 * heroku open: will send you to the url of your app after pushing it.
 * heroku logs --tail: to view information about your running app.
 * Control+C: to stop streaming the logs.
 ![Heroku](./Img/heroku.gif)