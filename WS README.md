# ComponentsWSPartTwo
 Week Five Components Worksheet Part 2

Each exercise will require the creation of a new component. Each component file should be created inside of a components folder within your exercise React project. Once the component is created, instantiate the new component within the App.js component for testing.
Component 

1. Create a SuperheroCreateForm component that will add a Superhero object to the array of objects in the App component state variable
a. The SuperheroCreateForm component will need to have a form with inputs for unique id, superhero name, primary ability, secondary ability.
b. On button click, it should add that superhero to the table.
c. HINT: create the add function in the App component and pass it as a prop to the
component that renders the table
d. HINT: this component will need a handleSubmit function that is called onSubmit of the
form and a handleChange function that is called onChange of the input tag
e. HINT: this will need to be a class component

2. Create a component that consumes a jokes API and displays the received data with the joke setup and punchline on the page in h1 tags inside the App.js component.
a. HINT: You will need to npm install axios to use the Axios library to make an HTTP request
b. HINT: The API call will be a AXIOS GET request contained within the component’s componentDidMount lifecycle method.
c. API Endpoint: https://v2.jokeapi.dev/joke/Programming?blacklistFlags=nsfw,religious,political,racist,sexist,explicit&amount=5