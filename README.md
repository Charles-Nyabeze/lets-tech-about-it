# Let's Tech About It 

      
![GitHub license](https://img.shields.io/static/v1?label=License&message=MIT&color=blue&style=for-the-badge)

# Description
A fullstack app built for tech posts and talk. A mysql database and CMS-style app built using Model View Controller (MVC) paradigm. Built using MySQL2, Express, Sequelize, Bulma, Handlebars and dotenv

![Lets Tech About IT ](https://user-images.githubusercontent.com/90402466/160191017-c4c5123e-5acf-4dde-808e-e441a5f5374c.png)


# Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Questions](#questions)

# Installation 

`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`

`npm install cloudinary`

# Usage

Run the commands in the terminal of the project and answer the prompted questions:

`mysql -u (username) -p`

Enter your password.

`source db/schema.sql`

`quit`

`npm run seed`
  
`npm start`

When you run node index in your terminal, you will be made to answer a series of questions. Once all questions are answered navigate to the dist folder as it will house the readme file that your responses will be stored to. Open a preview of your new README and ensure that everything is spelled correctly and that the links to your GitHub page and email work otherwise you will need to run the application again and reinput the correct information.

# License

> This project is using the MIT license.

# Contributing

If you would like to contribute to this project, fork this repository and clone your forked repository into your local machine, set the upstream as this repository and the origin as your forked repository, then use git pull upstream main to sync your local repo with the project repo. Then create a new feature branch which will house all your edits. Once finished push commits to your forked repository and then create a pull request! All contributions are encouraged!

# User Story

```
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions
```

# Acceptance Criteria

``` 
GIVEN a CMS-style blog site
WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
WHEN I click on the homepage option
THEN I am taken to the homepage
WHEN I click on any other links in the navigation
THEN I am prompted to either sign up or sign in
WHEN I choose to sign up
THEN I am prompted to create a username and password
WHEN I click on the sign-up button
THEN my user credentials are saved and I am logged into the site
WHEN I revisit the site at a later time and choose to sign in
THEN I am prompted to enter my username and password
WHEN I am signed in to the site
THEN I see navigation links for the homepage, the dashboard, and the option to log out
WHEN I click on the homepage option in the navigation
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
WHEN I click on an existing blog post
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
WHEN I click on the dashboard option in the navigation
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
WHEN I click on the button to add a new blog post
THEN I am prompted to enter both a title and contents for my blog post
WHEN I click on the button to create a new blog post
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
WHEN I click on one of my existing posts in the dashboard
THEN I am able to delete or update my post and taken back to an updated dashboard
WHEN I click on the logout option in the navigation
THEN I am signed out of the site
WHEN I am idle on the page for more than a set time
THEN I am automatically signed out of the site
```
# Walkthrough

> [Checkout the walkthrough](https://www.loom.com/loading)

# Questions
Please contact me through the following methods!

> [My Github account](https://github.com/charles-nyabeze)

> <a href="mailto:charlesnnyabeze@gmail.com">My Email</a> 
