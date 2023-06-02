# Project-Planner

#This code snippet showcases a simple project management application built using JavaScript and DOM manipulation. The application displays two different project lists: active projects and finished projects. Let's walk through the code step by step:

The DOMHelper class contains helper methods that facilitate DOM operations. The clearEventListeners method removes all event listeners from an element, while the moveElement method is used to move an element to a specified destination.

The Component class defines the basic properties and behaviors of a component. The detach method removes a component from the DOM, and the attach method adds a component to a specified position.

The Tooltip class is a subclass that represents a specialized tooltip view of a component. The closeTooltip method closes the tooltip, and the create method constructs and positions the tooltip component.

The ProjectItem class represents a project item. The showMoreInfoHandler method displays the tooltip when the "Show More Info" button is clicked, while the connectMoreInfoButton and connectSwitchButton methods attach event listeners to the buttons.

The ProjectList class manages the list of projects and performs necessary operations for adding or removing projects from the project list.

The App class serves as the main entry point of the application. The init method creates the project lists and sets up the event handlers. The startAnalytics method loads the analytics script.

By examining this code snippet, you can gain insights into fundamental concepts and practices of front-end development and JavaScript. It covers topics such as DOM manipulation, event listeners, and component-based development.

live site --> https://hilmi77.github.io/Project-Planner/

