## Folder Structure

### We would like to release `kasfy` as MVC Structure
Kasfy Framework is based on the Model-View-Controller development approach. MVC is a software approach that separates application logic from presentation. In practice, it permits your web pages to contain minimal scripting since the presentation is separate from the Node.js scripting.

- **The Model** represents your data structures. Typically your model classes will contain functions that help you retrieve, insert, and update information in your database.
- **The View** is the information that is being presented to a user. A View is normally the HTML CSS and optionally JavaScript programs. 
- **The Controller** serves as an intermediary between the Model, the View, and any other resources needed to process the HTTP request and generate a web page.

### Folder Structure
```nash
|--app
  |--controllers
  |--middleware
  |--models
  |--providers
|--config
|--database
|--node_modules
|--public
|--routes
|--views

```

## Folder Connection Diagram

```nash
|--routes
|    |--app/controllers
|    |      |--app/models
|    |      |--app/middleware
|    |      |--app/providers
|    |      |--views
|    |            |--public
|--config

```


<br/><br/><br/><br/><br/><hr/>
This page is <b>open source</b>. Noticed a typo or something's unclear? [Improve this page on GitHub](https://github.com/kasfy/kasfy.github.io)