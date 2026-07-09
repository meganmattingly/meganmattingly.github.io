# Graduate Projects

Over the course of my masters program, I had the opportunity to work on a variety of different projects, both inside and outside of the classroom. These experiences introduced me to new analytic techniques, built confidence in my existing skills, and taught me more about applying technical skills to business problems. They are described in detail below. 

## Graduate Assistantship at the Center for Business Analytics and AI

Perhaps the most impactful experience I had during the last year was my graduate assistant role at the [Center for Business Analytics and AI](https://www.business.uc.edu/about/centers-partnerships/business-analytics.html). The CBAI partners with Cincinnati-based companies to allow students to work on analytic projects in a business setting. The student(s) assigned to a project are partnered with a department faculty member to assist with the technical work, but there is also an emphasis on project management. Students are responsible for scheduling and leading weekly meetings with the client, providing progress updates, and maintaining proper documentation, in addition to the analytic work. At the end of the semester, students present their work to the client and CBAI leadership. I had the opportunity to work on two of these projects, one in Fall 2025 and one Spring 2026. 

Since we were required to sign NDAs, I'm not able to share code examples or specific results for these projects, but I can give an high-level overview. In the fall, I worked with HBH Holdings and Enerfab Process Solutions on a natural lanuage processing project. HBH/Enerfab work in the construction and fabrication industry, so they must submit bids to customers to try and win their business. However, the specification documents for a single project are often hundreds of pages, making the review and bid preparation process difficult and time-consuming. The goal for the semester was to develop an AI tool prototype that can accept user questions, search the spec documents, and generate clean, concise answers. To accomplish this, we developed a RAG pipeline and built a simple web interface over the top. Since accuracy is very important for the engineers that would be using this tool, we also returned the source files used to generate the response to help build trust.   

In the spring, I worked with the UC Football Sport Science department on a data engineering project. They collect a large amount of athlete monitoring data, but it is currently being stored across many different platforms, which limits automation and complicates reporting and analysis. As the program continues to grow, a more scalable solution is needed to support sport science initiatives. This project is going to be a long-term partnership between the CBAI and UC Football, but our goal for the first semester was to develop a prototype for the database infrastructure and begin ingesting the highest-priority data sources to validate our approach. We decided to use a medallion architecture approach and our planned tech stack included external APIs, AWS lambda functions, S3 storage buckets, and Snowflake external tables. The future steps for this project are to ingest all available data sources into the bronze layer and begin transformations for the silver and gold layers. Once this is complete, the team will be able to build automated dashboards and develop more complex models using the clean data. 

Another benefit of working with the CBAI was the opportunity to attend events hosted by the center. In the fall, I volunteered at the [Data Science Symposium](https://www.business.uc.edu/about/centers-partnerships/business-analytics/events/data-science-symposium.html), where I was able to engage with industry professionals and hear more about how the skills I was learning about in the classroom were being applied. In the spring, I volunteered again at the [Analytics and AI Summit](https://www.business.uc.edu/about/centers-partnerships/business-analytics/events/analytics-summit.html), which is a larger event. Since this event took place in May and I had fully completed two projects, I was able to present posters about my work (pictured below). I had conversations throughout the day with fellow students, faculty members, and industry leaders about the CBAI and the skills that I developed there.

<p align = "center">
  <img width="600" height="400" alt="hbh_poster" src="https://github.com/user-attachments/assets/bdd71058-3207-46b4-bf66-10fb911a2916" />
</p>
<p align="center"><em>This poster describes the HBH/Enerfab project completed in Fall 2025.</em></p>

<p align = "center">
  <img width="600" height="400" alt="uc_football_poster" src="https://github.com/user-attachments/assets/d3a69e65-46be-4bd8-bc08-c3026c4ee3c0" />
</p>
<p align="center"><em>This poster describes the UC Football project completed in Spring 2026.</em></p>


## Capstone Research Project

The most comprehensive project of the masters program was my capstone research project. Since the program was only one year, this means that the project was completed alongside a full courseload in the spring semester, essentially like an independent study. I wanted to work on a project that blended my personal interests with technical work, so I decided to explore soccer analytics. I found data related to player performance and their market valuations and began developing predictive models. The results were showcased using an interactive Tableau dashboard (pictured below), making them accessible and actionable for non-technical users. This [GitHub repository](https://github.com/meganmattingly/capstone-research-project) contains the associated data and code files used to complete the project, as well as a more in-depth description of the analytic approach and results. 

<p align = "center">
<img width="600" height="300" alt="Screenshot 2026-06-25 160613" src="https://github.com/user-attachments/assets/25fbb3e1-bab1-41ff-b278-dc95f6b54497" />
</p>

The [project abstract](assets/mattingly_megan_capstone_coverpage_abstract.docx) and [presentation slides](assets/mattingly_megan_capstone_presentation.pptx) are available for download here. 

## Coursework

My [GitHub portfolio](https://github.com/meganmattingly) also contains some of the projects completed during my masters courses. Any necessary data and code are hosted there, but some additional files can be found here. 

#### Forecasting and Time Series Analysis

The weekly assignments and final project for this course were written using Quarto documents, which unfortunately do not render properly on GitHub. I've included the HTML versions below:

- [Assignment 2: Data Decription, Exploratory Analysis, and Decomposition](assets/Assignment_2.html)

- [Assignment 3: ARIMA Modeling](assets/Assignment_3.html)

- [Assignment 4: Model Selection and Validation](assets/Assignment_4.html)

- [Assignment 5:Forecasting with Prophet](assets/Assignment_5.html)

- [Final Project](assets/Final_Project.html)

