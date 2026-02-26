# CS-340

## Portfolio Reflection - CS-340 Project Two (Grazioso Salvare Dashboard)

### Maintainable, readable, and adaptable programs
To write maintainable and readable programs, I focus on separating responsibilities and keeping my code organized. In this course, I created a separate CRUD Python module to handle all MongoDB database operations. This allowed the dashboard code to focus only on the user interface and interactive components. By separating the database logic from the dashboard layout and callbacks, the code became easier to debug, update, and expand. If changes are needed in the database connection or filtering logic, I can modify the CRUD module without rewriting the entire dashboard. In the future, this CRUD module could be reused in other applications that need to connect to the same database or similar datasets.

### How I approach problems as a computer scientist
When approaching a problem, I break it into smaller, manageable steps and test each part individually. For this project, I first ensured that I could successfully connect to MongoDB and retrieve data. Next, I built the dashboard layout, and then I connected the interactive components such as radio button filters, the data table, the pie chart, and the geolocation map. This project differed from earlier assignments because it required integrating multiple technologies and meeting specific client-style requirements. Moving forward, I will continue using structured problem-solving strategies such as building a working baseline first, testing frequently, and debugging systematically to ensure reliable results.

### What computer scientists do and why it matters
Computer scientists design systems that organize data, automate tasks, and provide meaningful insights that help organizations make informed decisions. In this project, the dashboard allows Grazioso Salvare to quickly filter and analyze animal shelter data to identify dogs suitable for specialized rescue training. Instead of manually reviewing records, users can interact with dynamic filters, charts, and maps to find relevant information efficiently. This demonstrates how computer science solutions improve productivity, accuracy, and decision-making within an organization.
