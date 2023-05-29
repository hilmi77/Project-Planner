# Project-Planner

#This code is used to create a project list and a web application that represents the project elements. Below is a simpler version of the code:

The DOMHelper class has helper functions related to the Document Object Model (DOM). It includes two static methods: clearEventListeners and moveElement. clearEventListeners is used to remove all event listeners from an HTML element, while moveElement is used to move an HTML element to another target element.

The Component class defines the basic properties of components. It provides methods to add and remove the component to/from a host element (or default to the <body> element) by taking the hostElementId and insertBefore parameters.

The Tooltip class represents a tooltip component. It takes a callback function as the closeNotifierFunction parameter. The create method creates the tooltip element and adds event listeners. The closeTooltip method removes the tooltip and triggers the callback function.

The ProjectItem class represents a project item. It takes the id, updateProjectListsFunction, and type parameters. The showMoreInfoHandler method creates and attaches the tooltip when the "More Info" button is clicked. The connectMoreInfoButton method adds an event listener to the "More Info" button. The connectSwitchButton method adds an event listener to the switch button and updates the button text. The update method is used to update the project list.

The ProjectList class represents the project list. It takes the type parameter. The setSwitchHandlerFunction method sets a switch function to manage the project switch. The addProject method adds a project and moves the item to the target element using DOMHelper. The switchProject method changes the project's status and updates the project list.

The App class is used to initialize the application. The init method creates the active and completed project lists and sets up the switch functions.
