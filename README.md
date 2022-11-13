# 🛸 The Martian Zoo

In this challenge we are on an alien ship with the mission to gather some Animals from earth.

We want to make a simple application that allows you to dynamically teleport Animals to the ship's cargo and keep a manifest of the animals on it:

- There should be a select input that allows the user to pick animals from a list.
- Once an animal is selected clicking on the button "Teleport" will add the animal to the Manifest's list.
- Manifest's list will display all the animals that have been teleported, if no animals have been added it should display an empty state.
- Each item should be given a button that can be pressed to "Free" the Animal back to nature.


## Steps 🏗️

To complete the exercise, follow the steps below, and make sure that the list behaves as described above.

1. To start with, download a copy of our boilerplate and get familiar with it's content.
2. Create three variables that hold references to the list (`<ul>`), `<select>`, and `<button>` elements.
4. Listen to the changes of the `<select>` and store the Animal in a variable.
4. Create a function that will run in response to the "Teleport" button being clicked.
5. Inside the function create the DOM needed for the Animal's item (as in the design).
7. Append the list item as a child of the list.
8. Attach an event handler to the delete button so that, when clicked, it will delete the entire list item (`<li>...</li>`).

### Bonus

- Make the application look as in the Example.
- Create an Empty state.
- Make a logic so that if an animal is already on the list it can't be added again.


## What's in this project?

← `README.md`: That's this file.

← `index.html`: This is the main web page for your site. The HTML defines the structure and content of the page using _elements_. You'll see references in the HTML to the JS and CSS files. Try clicking the image in the center of the page!

← `style.css`: CSS files add styling rules to your content. The CSS applies styles to the elements in your HTML page. The style rules also make the image move when you click it.

← `script.js`: If you're feeling fancy you can add interactivity to your site with JavaScript. The code in the JavaScript file runs when the page loads, and when the visitor clicks the button you can add below.

Open each file and check out the comments (in gray) for more info.
