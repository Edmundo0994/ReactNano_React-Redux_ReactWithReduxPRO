#Info taked from Udacity class#

*Asynchronous Redux Lesson*

In this lesson, we're going to be working with a (simulated) remote database. We'll use a provided API to interact with this database.

The important skill that you'll be learning in this lesson is how to make asynchronous requests in Redux. If you recall, the way Redux works right now is:
 -store.dispatch() calls are made
 -if the Redux store was set up with any middleware, those functions are run
 -then the reducer is invoked

But how do we handle the case where we need to interact with an external API to fetch data. For example, what if our Todos app had a button that would load existing Todos from a database? If we dispatch that action, we currently do not have a way to wait for the list of remote Todo items to be returned.

After going through this lesson, you'll be able to make asynchronous requests and work with remote data in a Redux application.

