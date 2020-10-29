# Web-Design - Latitude Analysis Dashboard
For this challenge I'll be creating a visualization dashboard website using stock visualizations created from a previous challenge. Specifically, I'll be plotting weather data.

In building this dashboard, I'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. I'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

## Website Requirements
The website will consist of 7 pages total, including:
1. A landing page containing:
</br>- An explanation of the project.
</br>- Links to each visualizations page. There will be a sidebar containing preview images of each plot, and clicking an image will take the user to that visualization.

2. Four visualization pages, each with:
</br>- A descriptive title and heading tag.
</br>- The plot/visualization itself for the selected comparison.

3. A "Comparisons" page that:
</br>- Contains all of the visualizations on the same page so we can easily visually compare them.
</br>- Uses a Bootstrap grid for the visualizations. (The grid will be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens).

4. A "Data" page that:
</br>- Displays a responsive table containing the data used in the visualizations.
</br>- The table will be a bootstrap table component.
</br>- The data will come from exporting the .csv file as HTML, or converting it to HTML.

The website will, at the top of every page, have a navigation menu that:
</br>- Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
</br>- Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
</br>- Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
</br>- Is responsive (using media queries). The nav will have similar behavior as the screenshots "Navigation Menu" section.
</br>- Finally, the website will be deployed to GitHub pages.

