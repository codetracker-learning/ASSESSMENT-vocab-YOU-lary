# vocab-YOU-lary

In this student assessment, you will be creating an application that allows users to CRUD vocabulary cards.

## Get Started
- Use the webpack template to create the project on your github account
- Setup your firebase project and create the `.env` file with your keys. (Reference the Firebase videos if you need help getting started)
- Plan your project. Take no more than an hour to plan (ERD, Flow Chart, Postman)
- START CODING!

## Learning Objectives
- Single Responsibility Principle (each component/function should have one job)
- Import/Export modules
- DOM manipulation with Vanilla JS
- DOM querying with Vanilla JS
- Representing data as HTML
- Usage of semantic HTML5 tags
- Asynchronous Programming
- Promises 

## Tools To Use:
- Postman for API testing
- Firebase for database, rules, and authentication
- Webpack template (Located in your cohort repo)
- dbdiagram.io for creating your ERD
- Figma, google slides, or paper for flow charting your application
- Axios for requests

# MVP Requirements
- [MVP Wireframe](https://www.figma.com/file/IW4jF3GnzCFLYbEXlgFNIZ/MVP)
- An ERD of your data
- Use Firebase for DB and authentication
- Technical Flow chart (timebox this)
- The app has a navigation bar
  - A logo
  - Logout button
  - Create Entry
  - Any other options you would like to add
- Completed README
- Loom Video (On your README)

**The most basic requirement for this project is that a user can:**
- Login and Logout of the application
- CREATE a vocabulary entry:
  - Title
  - Definition
  - Language/Tech
  - Time submitted - Not on form. Handle in your JS
  - Author ID - Not on form. Pull from User object.
- READ entries
- UPDATE entries
- DELETE entries
- Filter by language/tech
- Style your application using your own creativity!

## Stretch 1
- [Stretch 1 Wireframe](https://www.figma.com/file/UC3Gi8HFRkZY8OIMOAUgL4/Stretch-1)
- Allow users to order entries alphabetically, newest, oldest

## Stretch 2
- [Stretch 2 Wireframe](https://www.figma.com/file/UC3Gi8HFRkZY8OIMOAUgL4/Stretch-2)
- Users can search vocabulary entries
- Users can only see the vocabulary entries that they created
- Users can add Language/Tech to the database and refrerence it on their vocabulary entries
- Users can only see the Languages/Tech categories that they created

## Stretch 3
- [Stretch 3 Wireframe](https://www.figma.com/file/KgbkfaoRd5F8Q4qZ3G2Bg2/Stretch-3)
- Users can mark an entry as public or private
- If an entry is public, anyone can view it. If it is private, only the user who created it can see it
- If an entry is public, any user can copy the entry to their own set of entries and then CRUD on the new/copied entry
