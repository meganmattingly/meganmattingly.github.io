# Undergraduate Projects

Although my bachelors degree is in mathematics, I knew that I wanted to eventually work in a more applied field. During my junior and senior years, I was exposed to statistics and data science concepts through electives and research opportunities. I believe that my math background makes me a better analyst because I have strong problem-solving skills and I know how to uncover and explain the "why" behind solutions.  

## Independent Study- Machine Learning

Transylvania University began offering a Data Analytics minor in 2025, but since I had already graduated, I was not able to complete it. However, I did have the opportunity to help develop the program curriculum. I completed an independent study with Dr. Michael Kelly in the spring of 2024 that focused on machine learning. We studied *Machine Learning with R* by Brett Lantz, which explains the methodology behind algorithms and also offers hands-on examples for implementation. The book covers supervised and unsupervised learning methods, as well as regression and classification algorithms. We focused on k-NN, Naive Bayes, decision trees, association rules, and k-means before also discussing data preparation and model evaluation. I created outlines for each chapter covered and we worked through the code examples together to learn how to apply each model. This work eventually became the foundation for the DATA-3444 course, which is the capstone for the Data Analytics minor. Even though I was not in a traditional classroom setting, I still learned a lot during that semester, which served me well in future academic and professional projects.  

## Summer Research Experience 

During the summer of 2023, I recieved a grant from Transylvania University to work on a research project with a faculty mentor. I worked with Dr. Michael Kelly and we utilized mathetical modeling to survey information spread on online networks. This refers to the way in which information moves throughout a population. There are several common analogies often used to model this phenomenon, including an infectious disease or a forest fire. We took inspiration from these methods when developing our approach. 

The first model we created is an absorbing Markkov chain matrix model. This is a probabilistic model that demonstrates how users move through stages of information spread and what the long-term behavior of the system is. Next, we developed the forest-fire algorithm, which builds off of the Markov chain. It is a graph-based algorithm that incorporates a spatial aspect to model the way that users are connected to each other online. Finally, we developed a differential equation model, based on the classic SIR model for disease spread. We analyzed the behavior of the model by finding equilibria and calculating the basic reproduction number. For all three models, we ran simulations to uncover long-term trends and dicussed assumptions and limitations. 

The [research report](assets/summer_research_report.pdf) provides more explanation of the technical approach for each model, as well as in-depth analysis of results. I also gave a [presentation](assets/summer_research_presentation.pdf) on my findings at an on-campus symposium for students who had completed summer research.

## Coursework

#### Applied Statistics

The Applied Statistics course was offered as an elective during the fall semester of my junior year. We covered a variety of topics in this course, including EDA, data visualization, regression, and statistical tests, like ANOVA and Chi-squared. Perhaps most importantly, this was my first introduction to coding in R, which is a skill that I have continued to use in many projects. 

The final project required us to find a data set of interest and explore three questions using techniques learned during the course. I wanted to blend my personal and technical interests for this project, so I chose a data set on Women's World Cup statistics, which contains information on participating teams from every iteration of the tournament. I attempted to answer the following questions: 

- Is there a difference in the median number of goals scored per game between continents?
  
- Which variables are the best predictors of winning the Women's World Cup?
  
- Which variables are the best predictors of how far a team makes it into the World Cup?

To investigate these questions, I utilized the Kruskal-Wallis test (similar to ANOVA, but for medians), a logistic regression model, and an ordinal logistic regression model, respectively. 

The [final report](assets/applied_stats_report.pdf) and [presentation slides](assets/applied_stats_presentation.pdf) contain more information on the statistical approach and result for each question above. 

#### Mathematical Modeling

The Mathematical Modeling course was offered as an elective during the spring semester of my junior year. I was introduced to a variety of new modeling concepts, including matrix models, stochastic simulations, and differential equations. Our task for the final project was to choose a topic and develop a mathematical model to analyze the system. This course served as the foundation for my summer reseach project, which is described above. 

For my project, I chose to model information spread on online networks. This is often done by equating information spread to a natural phenomenon, like a forest fire or an infectious disease. I began by creating a basic SIR differential equation model to serve as a baseline, before expanding this to include a reinfection rate. Next, I adapted a forest fire model into an absorbing Markov chain matrix model, which uses probability to showcase the way that users move through each phase. For both models, I analyzed simulations to determine short and long-term behavior of each system and compared the results.   

The [final report](assets/math_modeling_report.pdf) and [presentation slides](assets/math_modeling_presentation.pdf) provide more information on model development and results. 
