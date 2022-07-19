# Redux-Store

[Redux-Store Link App](https://damp-taiga-12760.herokuapp.com/)
You’ll enhance an existing e-commerce platform called Redux-Store. To do this, you’ll centralize all of the application's data in state globally to make it easier to share state across the entire application. You’ll also create a shopping cart for the application, add offline functionality, and process secure online payments with a service called Stripe.

# User Story 

AS a senior engineer working on an e-commerce platform
I WANT my platform to use Redux to manage global state instead of the Context API
SO THAT my website's state management is taken out of the React ecosystem
Acceptance Criteria

# Acceptance Criteria

GIVEN an e-commerce platform that uses Redux to manage global state
WHEN I review the app’s store
THEN I find that the app uses a Redux store instead of the Context API
WHEN I review the way the React front end accesses the store
THEN I find that the app uses a Redux provider
WHEN I review the way the app determines changes to its global state
THEN I find that the app passes reducers to a Redux store instead of using the Context API
WHEN I review the way the app extracts state data from the store
THEN I find that the app uses Redux instead of the Context API
WHEN I review the way the app dispatches actions
THEN I find that the app uses Redux instead of the Context API

# Mock-Up

This section reviews the web application's general appearance and functionality.

The following animation shows how a user can register using the Signup page and then navigate to the Products page:

![22-state-homework-demo-01](https://user-images.githubusercontent.com/86209350/179861967-e1779980-89f3-40f5-b5dd-14d4a5dd24f2.gif)


The following animation shows how the user can select a category, choose a product, view details about it on the product page, and add and remove it from their shopping cart:

![22-state-homework-demo-02](https://user-images.githubusercontent.com/86209350/179861982-adff24ca-16ac-4dd1-97ef-6011ced9ad42.gif)

Finally, the user can checkout by going to their shopping cart, as shown in the following animation:

![22-state-homework-demo-03](https://user-images.githubusercontent.com/86209350/179861993-d825b41c-dab3-4b55-a69a-6c9b3c86de3d.gif)

