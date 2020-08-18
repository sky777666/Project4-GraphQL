# Luke Myers Project 4 - GraphQL
## Application Name: MyNotes

## Intro

#### Ideas for Technologies to Use:
Vue.js (frontend framework).
GraphQL (frontend querying language. Would recommend using with Hasura so that you don't have to take on Apollo and Prisma breaking change errors).
Unity (in C#)Integrating a Stripe frontend and backup to build a test level functional ecommmerce siteD3.js (a data visualization javascript library)
React-Bootstrap-Table or another React Table Library to create dynamic tables based on a database you create and seed


#### Name of app
MyNotes

#### Your name/team members
Luke Myers / Self project no team.

#### New tech you plan on using

GraphQL &  Apollo


#### How do you plan on learning/implementing this new technology?
Using educatinal material online. I would like to find tutorial video's also.

#### What is your goal with this project?
My goal is to make a fully working application that is frunt end heavy showcase Microscopic life. Lots of pictures of microbes. If I do not make an API - then I would like to use GraphQL to route call and Mutations of a DataBase a good example of this would be a Notes Application. 

#### Who is the user for your app?
 All people can use it but according to ( dshs.texas.gov ) An estimated 5.8 million Americans of all ages are living with Alzheimer's disease in 2020. So it is for these people that I am making this app. I am making it for them. So the ideal user is anyone who needs to make notes to help them remember things. 

#### Any potential roadblocks you think you might run into?
I know nothing about these two new tech's " SQLlite and GraphQl " so the only road block I see is not being able to get it up and running in the 5 or 6 days we have.

#### Include Graphics or Links to:

This is my intal plan but as you will see this inital plan changed as I got deeper into GraphQL. 
See my Trellio Link for Planning Here: https://trello.com/b/z32qSKhB/its-a-small-world-now

## About this Project

### Frontend Tecknologies Used:

- HTML:5
- CSS:3
- JavaScript
- React
- Node 
- Apollo
- React Router
- GraphQL

### Backend Tech
- GraphQL
- Express
- Express-GraphQL
- Mongoose ORM
- MongoDB


### GraphQL Resolvers Used

- Query

- Mutations

### Example of my GraphQL resolvers

![](https://i.imgur.com/wMBJ8bD.png)
:::


## :memo: My Story about this project


![](https://montykamath.files.wordpress.com/2018/02/graphql.png?w=210&h=210)
:::

 On Friday we were tasked with learning, exploring, and building an application with a new technology. 
When I started out I wanted to build a fancy design heavy frontend with React.js to showcase my growing frontend React skills. For my new technology I wanted to implement a SQLite database. Once I got that up and running I found out how easy it was to put a SQLite database into any project. So I decided to move on to GraphQL. My first thought was to build a API and use GraphQL and an SQLite DB as a read only DB for images of microscopic life. Getting started with GraphQL I was quickly brought to HASURA. There I set up a Postgres DB and a Heroku account and started on the Hasura tutorial. I found out how easy it was to make a Postgress DB with Hasura as well as make and edit DB tables. I also found how easy or a tool Hasura makes working with GraphQL. 


![](https://media-exp1.licdn.com/dms/image/C4E0BAQEIx9q7nmDydg/company-logo_200_200/0?e=2159024400&v=beta&t=qgCOpETll3y_iCIfqRKldPpTug9uUYy0O5Zd3rstslI)
:::

Now it is Tuesday. I worked all weekend! I finished the Hasura tutorial, built 2 backend's ( SQLite & Postgress) and got a GraphQL server stared. I still had now frontend or design idea. I was have technical issues getting any of my frontend server code or frontend style to hook up to my Hasura. So with time running thin I decided on a new plan. I would take on a frontend approach and use what I knew to build the frontend and the backend and find a tutorial that could walk me through connecting the two with my working GraphQL. After many long hours of typing, searching and debugging I finnaly have a completed and fully functional application based on GraphQL. It is called MyNotes. MyNotes uses GraphQL to manage queries to the DB and allowed users to update their notes or "posts" and even delete them. It is light on design but also very clean and user friendly. 


- [X] We were tasked with 
- [x] Create a  HackMD README (this one!)
- [X] Write Basic Pseudo Code of code that will be  needed.
- [X] Started coding !

:rocket: 










> Drag-n-drop image from your file system to the editor to paste it!





### Code Examples


- Code block with color and line numbers show some code like this：
```javascript=16
import mongoose from "mongoose";
const Schema = mongoose.Schema;

const NoteSchema = new Schema({
  title: {
    type: String,
    required: true
  },
  content: {
    type: String,
    required: true
  },
  date: {
    type: Date,
    default: Date.now
  }
});

export default mongoose.model("note", NoteSchema);


```



#### References, Resources, and Citations for this project

- Hasura Basics
https://hasura.io/learn/graphql/hasura/introduction..

- Auth0 
https://auth0.com/docs/microsites/add-login/add-login-single-page-app..

- GraphQL Docs
https://graphql.org/

- Appollo 
https://www.apollographql.com/

- GraphQl & React I
blog.bitsrc.io/how-to-build-a-note-taking-app-with-graphql-and-react-part-1-of-2-febf1aeda091..

- GraphQL & React II
blog.bitsrc.io/how-to-build-a-note-taking-app-with-graphql-and-react-part-2-of-2-b1f4f40361a..


- SQLite and SQLiteBrower a tool for that can import excel spreadsheets into SQLiteDB
https://sqlitebrowser.org/

- Table of Content
[ToC]
