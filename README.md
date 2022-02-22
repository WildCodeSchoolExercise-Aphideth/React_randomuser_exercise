# REACT Random User - Exercise
## Disclaimer

**HAVE FUN** :smiley:


## :zero: Setup

You are starting the exercise from scratch ! So you need to install everything.
You can use : [create-react-app](https://create-react-app.dev/)


## :one: React

**In this step, you will create a web-app using React, that displays random users from one of our API !**

You can find the API documentation there :

- https://randomuser.me/api/?results=30

### Starting point

- You can wipe all the boilerplate jsx code in `App.jsx`
- Then, create a `<Header />` component that displays a cool welcome message.
- Pass a `name` prop to this component, to display your website name (_react game_ if you don't have any idea)


### Some list ?

- Your next mission is to display the full list of users.
- Start by creating two new components `<UsersList />` and `<User />`.
- In the `<UsersList />` component, you will need to get the list from the API, and map it in your jsx. For each user you get from the API, display a `<User />` component.
- Your `<User />` component will need some props to display the user informations. There are plenty of informations you can use (name, gender, image, ..._). Display them in the format of your choice !


### Filtering

- Now that you are displaying all users, your next mission is to add a filter on this list.
- Add a `button` to the `<UsersList />` component, when you click on it, it will display only the male users. When clicking again on this button, the list should display all the users again.


### Congrats ! You did it ! :confetti_ball:
