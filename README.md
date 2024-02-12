# Submenus Application

React Application implementing submenu functionality using global Context

# Description

Context

- Global context for opening and closing the sidebar in mobile mode
- Page Id context with default value of null. Once the user moves the mouse over a link, pageId is set with the specific page ID.

Navbar

- Logo and a button to open the sidebar.
- Implementing openSidebar function from the global context.

SideBar

- Sublinks imported from data.jsx, iterating over the list, and displaying links in the component. Using the isSidebarOpen and closeSidebar functions from the global context to show/hide the sidebar.

NavLinks

- NavLinks in the Navbar. Iterating over Sublinks to render pages on the screen.

Submenu

- Implementing Page Id context. Based on the specific page ID, get the specific page from sublinks and render the page and links in the submenu.
