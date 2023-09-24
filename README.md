# Conquering_Responsive_Website
Building a website that adapts and looks good across various devices and screen sizes, from desktop monitors to smartphones.  


# Percentages vs Fixed widths
Websites are responsive by default you are the one that makes it unresponsive

Percentage : 
Elements with percentage width are responsive and adapt to the size of their parent container.

Example:
css
Copy code
.container {
    width: 80%; /* 80% of the parent container's width */
}

Fixed Width:
Elements will have consistent dimensions regardless of the parent container's size.
Example:

css
Copy code
.container {
    width: 600px; /* Fixed width of 600 pixels */
}

When to Use:

Use percentage widths when you want a flexible and responsive layout, especially for elements like containers and grids that need to adapt to various devices.
Use fixed widths when you need precise control over layout elements and when a consistent design is crucial, particularly for elements like logos, specific components, or when you have a clear desktop-oriented design.
Best Practice:

A combination of both approaches is often used, where containers and main layout elements use percentage widths for flexibility, while specific components or elements that need precise sizing use fixed widths. This hybrid approach provides the best of both worlds, allowing for responsiveness and precision where needed.


