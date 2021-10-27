# Vue Training

## Resources

[VueJS Docs](https://vuejs.org/v2/guide/index.html)

## Objectives

- Read through the `Essentials` portion of the Vue docs and follow along with the `/index.html` file. You should be able to just open the file in your browser to run it. eg: `file:///C:/Users/{UserID}/Desktop/DanielVueTraining/index.html`

- Use the tools learned in `Essentials` to expand the `/index.html` file into a full "Todo" app.

  - Can view a listing of reminder notes, one per line.

  - Can add a new reminder note with with user-supplied text.

    - Give a button that adds the note when clicked.

      - If no note is entered, the button click should do nothing.

    - If the textbox is focused, hitting `Enter` should add the note.

  - Can edit a reminder note to change its text.

    - Give a button that saves the edit when clicked.

      - If no note is entered, the button click should do nothing.

    - If the textbox is focused, hitting `Enter` should update the note.

  - Can remove a reminder note from the list.

  - Use a `computed` property to display a count of current total list items somewhere on the page.

  - Use a `watch`ed property to clear the entire todo list if the user types only the word "clear" into the textbox for adding a new note.

  - Provide a "Filter" textbox that can filter the notes list as the user types into it by searching for the filter text anywhere within the reminder notes.

    - An empty filter should display the entire list.

    - Use another `computed` property to display a count of current filtered list items somewhere on the page.
