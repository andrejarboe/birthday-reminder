# Birthday Reminders

This is a React application that displays a list of people with birthdays on the current day. It contains a main component called App that displays the list of people and a button to clear the list, and a subcomponent called List that displays the people.

## How useState is utilized
The useState hook is used in the App component to manage the state of the list of people. It initializes the state with the imported data, and provides a function to update the state when the clear button is clicked.

The state is destructured into two variables: people and setPeople. The first is the current value of the state, and the second is a function to update it. The setPeople function is passed to the onClick event of the clear button, and when the button is clicked, it sets the value of people to an empty array, effectively clearing the list.

## File structure
The application has two core react files:

* App.js: This is the main component that renders the list of people and the clear button. It imports the List component and the data from the data.js file.

* List.js: This is a functional component that takes the list of people as a prop and renders an article element for each person with their name, age, and image.

## Running the application
To run this application, you will need to have React installed on your system.

Clone this repository.
Navigate to the cloned directory.
Run npm install to install the necessary dependencies.
Run npm start to start the development server.