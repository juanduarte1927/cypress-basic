# Cypress Basics

Welcome to our first exercise with Cypress.

To get started, execute the following command in your terminal (please ensure that you are in the project's root directory):

```bash
npm install

Now, you are ready to write your first automated test!

Navigate to `cypress -> e2e -> exercise1.cy.js.` Inside the it block, you can begin writing your code.

## Challenge

Automate the following acceptance criteria:

- A user wants to contact Huge by submitting only the required information on this page:  [Hugeinc Form](https://stg.hugeinc.com/contact/)
Push your changes to the master branch in your repository 


### Tips

Here are some useful commands and hints:

cy.get('selector').click(): Select an element and click on it.
cy.get('selector').type('some word'): Select an element and type text into it.
cy.visit('www.something.com'): Open a URL in the browser.
cy.get('selector').should('be.visible'): Select an element and check if it's visible on the screen.
cy.get('selector').should('exist'): Select an element and check if it exists in the DOM.
By using these commands in the correct order, you can successfully complete the challenge.

