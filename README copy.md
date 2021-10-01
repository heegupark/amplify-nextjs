# kanban

> - Maintained by: `Heegu Park`

## Features
1. It creates url based on project name
2. Iniitially, it creates fout columns - Plan, Progress, Complete, Archive(hidden)
3. Adding a column creates a new column data in `column` document
4. Updting a column updates the column data in `column` document
5. Adding a card creates a new card data in `card` document
6. Updting a card updates the card data in `card` document
7. Deleting a card deletes the card data from `card` document
8. Moving the column updates `columnOrder` in `route` document in database
9. Moving the card updates `order` in `card` document in database
10. Updating the project name updates the `project` in `route` document and redirect to new url based on new project name

## Technologies
1. Mainly used Typescript, React with Next.js for server-side rendering to create all HTML elements
2. Primarily used React Hooks and Next.js
3. Used AWS EC2 for web and API server

## Planned Features
1. User can create a project name.(If the project name is empty, it will create a random string.)
2. User can have its own links.
3. User can create a column.
4. User can create a card.
5. User can move a column to reroder.
6. User can move a card in a column or to another column to reorder.
7. User can edit a project name.
8. User can edit a column title.
9. User can edit a card title or a card subtitle.
10. User can delete a column.
11 User can deleta a card.
12. User can create a checklist.
13. User can delete a checklist.
14. User can add an activity.
15. User can view activities.
16. User can view the card information.


## Lessons Learned
1. Experienced Next.js for server side rendering and its structure
2. Experienced TypeScript for building a new application
3. Experienced Next.js `next/link` to dynamically redirect to the link
4. Experienced to deal with various functions of React Hooks
5. Used MongoDB for storing data
5. React and JavaScript Object Oriented Programming for better functionalities and to increase the re-usage of codes
6. Experienced to deploy the application built up on top of Next.js into AWS EC2

## Live Site
* You can see and test the live version here: <a href="https://kanban.heegu.net" target="blank">kanban.heegu.net</a>

## Screen shot
[Desktop]

![Omega Kanban](https://github.com/heegupark/omega-kanban/blob/master/kanban-ss-002.gif)
