# Client - Level 2

You have to create a similar HTML page than in level 1, but this time using React and ES6 (Ecmascript 2015). Don't worry, we've made the basic configuration for you (so you don't have to deal with webpack).

The needed files to get started are here. You can work in this folder or copy to another place. Just do:

```bash
npm install
npm start
```

Wait until the webpack-dev-server has finished creating the bundle and visit http://localhost:3000.

Some clarifications:
- You can use React's state, you don't need to install any external state manager (like Redux).
- It's recommended (although not required) that you create more than one React component.

Now you have to follow the same specifications than in level 1.

- On the top of the screen, it has to render two buttons:
  - **Display all posts**
  - **Display gadgets posts**
- The *Display all posts* button should fetch the first 5 posts from [demo.worona.org](https://demo.worona.org).
- The *Display gadget posts* button should fetch the first 5 posts of the category **gadgets** from [demo.worona.org](http://www.govoid.es).
- The API endpoint is https://demo.worona.org/wp-json/wp/v2/posts.
- The API documentation is http://v2.wp-api.org/.
- Once fetched, you should display the titles in a list. A new fetch (using the other button) should replace those titles.

This is welcomed, but not required:
- A loading indicator.
