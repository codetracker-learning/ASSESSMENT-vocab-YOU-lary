# vocab-YOU-lary

In this student assessment, you will be creating an application that allows users to CRUD vocabulary cards.

## Get Started
- Use the webpack template to create the project on your github account
- Setup your firebase project and create the `.env` file with your keys. (Reference the Firebase videos if you need help getting started)
- Plan your project. Take no more than an hour to plan (ERD, Flow Chart, Postman)
- START CODING!

## Learning Objectives
- Single Responsibility Principle (each component/function should have one job)
- import/export modules
- DOM manipulation with Vanilla JS
- DOM querying with Vanilla JS
- Representing data as HTML
- Usage of semantic HTML5 tags

## Tools To Use:
- Postman for API testing
- Firebase for database, rules, and authentication
- Webpack template (Located in your cohort repo)
- dbdiagram.io for creating your ERD
- Figma, google slides, or paper for flow charting your application
- Axios for requests

# MVP Requirements
- [MVP Wireframe](https://www.figma.com/file/IW4jF3GnzCFLYbEXlgFNIZ/MVP?node-id=0%3A1)
- An ERD of your data
- Use Firebase for DB and authentication
- Technical Flow chart (timebox this)
- The app has a navigation bar
  - A logo
  - Logout button
  - Create Entry
  - Any other options you would like to add

The most basic requirement for this project is that a user can:
- Login and Logout of the application
- CREATE a vocabulary entry:
  - Title
  - Definition
  - Language/Tech
  - Time submitted
  - Author
- READ entries
- UPDATE entries
- DELETE entries
- Filter by language/tech

## Stretch 1
- [Stretch 1 Wireframe](https://www.figma.com/file/IW4jF3GnzCFLYbEXlgFNIZ/MVP?node-id=0%3A1)
- Users can search vocabulary entries
- Users can only see the vocabulary cards that they created
- Users can add Language/Tech to the database and refrerence it on their vocabulary entries
- Users can only see the Languages/Tech categories that they created

## Stretch 2
- [Stretch 2 Wireframe](https://www.figma.com/file/IW4jF3GnzCFLYbEXlgFNIZ/MVP?node-id=0%3A1)
- Users can mark an entry as public or private
- If an entry is public, anyone can view it. If it is private, only the user who created it can see it
- If an entry is public, any user can copy the entry to their own set of entries and then CRUD on the new/copied entry
