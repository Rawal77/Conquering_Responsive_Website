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

# Em vs Rem
Em always looks on parent element (compounding effect)
REm always looks on root element 
But in the context of margin and padding em focuses on the font size of that element But it doesn't work for Rem as it is consistent

# Using max-width
using max-width ensures that content doesnot go away from one screen to all the way over the other.

# Using CSS units
Viewport width and height are fantastic units for setting on your viewport basis. Just make sure that you test things on your smaller devices too. As sometimes content may get overflown.

# Flexbox
Flexbox is a powerful CSS layout technique for creating responsive designs. It allows for fluid layouts by distributing and aligning elements within a container. With its intuitive properties, like flex-direction and justify-content, it simplifies creating layouts that adapt to various screen sizes. Flexbox enables easy rearrangement of items, optimal space utilization, and simplifies the creation of responsive web designs.



