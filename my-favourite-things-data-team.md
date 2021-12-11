# Data Team Management

## Agile Data Science

These are notes from the book Agile Data Science 2.0

* Agile methods applied to data science have an inherent tension: agile software development has a timeline of weeks while data science projects can span *months*. Maintaining constant pace is also difficult as data science projects have to iterate through multiple versions before hitting something valuable.
* The first principle is Iterate, iterate, iterate. When building a data product, the right result may only arrive after the fifth or fiftieth iteration of a table. It may require aggregation, filtering or new features. This is a reason why BI tools like Power BI or Tableau have taken hold - they are very easy to iterate on both the transformation and the visualisation front. Reusing transformations is important as well so they have to be performed upstream from the BI tool. If creating views is the engineer's and not the analyst's responsibility, iteration will happen downstream from the data warehouse in the BI tools. That is not great and tools like *dbt* help solve the issue.
* Ship intermediate output. At the end of a sprint, the product may not be able to be in its final shape so sharing work and assets as code is crucial. 
* Prototype experiments over implementing tasks. A reporting dashboard is not going to bring insight but experimenting in different ways it presents data might.
* Discover the critical path. THe critical path is the longest sequence of tasks that must be completed for a project to be completed on time. Analytics products have critical paths as well but they must be discovered through experimentation.
* Get meta. This essentially means avoiding documenting the end product but rather documenting the decisions and the process towards the final product.
* Data Science projects are usually shipped with "good enough" code. If the product becomes important, then increasing the quality of the code is paramount. Technical debt is a naturally occuring side-effect of data science projects.


https://drivendata.github.io/cookiecutter-data-science/#opinions
