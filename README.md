# Web_Visualizations Dashboard (Latitude)

This is a project that requires creating a visualization dashboard [website](https://ushaakumaar.github.io/Web_Visualizations) using visualizations created in a [past assignment](https://github.com/ushaakumaar/API-Challenge). Specifically, plotting [weather data](Resources/cities.csv).

## Programming Language / Applications - Used

  * HTML
  * CSS
    - Bootstrap
    - Media Query
  * Python
    - Pandas Library
  * Jupyter Notebook

## Website Design

In building this [dashboard](https://ushaakumaar.github.io/Web_Visualizations), created individual pages for each plot and a means to navigate between them. These pages contain the visualizations and their corresponding explanations. Created a landing page, a page where comparison of all of the plots could be viewed, and created another page where the data used to build the visualizations can be viewed.

The [website](https://ushaakumaar.github.io/Web_Visualizations) has 7 pages in total, including:

* A [landing page](https://ushaakumaar.github.io/Web_Visualizations/index.html) containing:
    * An explanation of the project.
    * Links to each visualization page. Created a sidebar containing preview images of each plot, and clicking an image will take the user to that visualization.
* Four Visualization pages
    * [Max Temperature](https://ushaakumaar.github.io/Web_Visualizations/Visualizations/max_temp.html) - Visualization Page
    * [Humidity](https://ushaakumaar.github.io/Web_Visualizations/Visualizations/humidity.html) - Visualization Page
    * [Cloudiness](https://ushaakumaar.github.io/Web_Visualizations/Visualizations/cloudiness.html) - Visualization Page
    * [Wind Speed](https://ushaakumaar.github.io/Web_Visualizations/Visualizations/wind_speed.html) - Visualization Page
* Each of the above visualization page contains:
    * A descriptive title and heading tag.
    * The plot/visualization itself for the selected comparison.
    * A paragraph describing the plot and its significance.
* A ["Comparisons" page](https://ushaakumaar.github.io/Web_Visualizations/Comparison/comparison.html) that:
  * Contains all of the visualizations on the same page so users can easily compare them visually.
  * Used Bootstrap grid and Media Query for the visualizations to display two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](https://ushaakumaar.github.io/Web_Visualizations/Data/data.html) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component.
    * The data was exported from [`.csv` file](Resources/cities.csv] as [HTML](Data/html_created_from_python.html) using Pandas [Jupyter notebook](Data/create_html_from_csv.ipynb) file.

The website at the top of every page, has a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). 

---

## Contributors

- Usha Saravanakumar ([ushaakumaar](https://github.com/ushaakumaar))
