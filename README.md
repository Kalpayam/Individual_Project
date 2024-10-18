Shipping Emissions at Port
-----


Using anonymised vessel emissions data from the NGO Transport & Environment, I built a pipeline in python to present an analysis on shipping emissions at port, to address a few questions raised by the NGO Transport & Environment.
The data includes hourly entries for carbon emissions, and geographical coordinates for 100 unique container ships.
![World map emissions](/media/port_emissions_map.png "Emissions at Port")
Purpose and Analysis
The aim of this project was to explore the environmental impact of container ships when stationed at port, where emission levels have health implications as well as climate impact. Emissions at ports are also interesting to be measured since they can be mitigated throgh the use of shore power. By identifying key patterns and offering actionable insights, this analysis provides information to the general public as well as legislators, and other stakeholders on port emissions and how to reduce them. These include:

I was asked by he NGO Transport & Environment to find policy-relevant insights on emissions at European ports, and explore the data for other insights that could be relevant for the general public or policy makers. North Sea ports of Hoek von Holland, Bremerhaven, and Felixstowe had the highest share of emissions due to congestiona and long waiting time, raising questions of public heallth as they are close to populated urban areas. These results are relevant for city and regional planners among other stakeholders. 
The results also show that 4% of global emissions from the container sector occur at ports. This percentage can be reduced to zero in theory with the intriduction and diffusion of shore side electricity, aloowing for the vessel to shut down her engines and stop emissions at port. 
The results also show a significantly higher rate of greenhouse gas emissions in African ports which is alarming and calls for scrutiny beyond national legislation. 
The analysis aligns with the course goal S16: to run an industry-relevant project showcasing my analytical and reflective capabilities. This topic is timely within the maritime industry. The project uses anonymised real data, as handled and shared by the NGO Transport and Environment with compliance to all relevant regulatory requirements. I have cleaned, organised, transformed and analyzed data and presented the results to the NGO Transport & Environment. The results included a notebook containing an interactive map viualising global emissions at port, a deck of slides, and an accompanying text, offering results as well as data-driven recommendations for reducing carbon footprints.

Independent Project Execution and Management
As part of achieving S16, I used Agile project management practices to structure my work. I broke down the project into smaller tasks using a Kanban board, ensuring steady progress:

Backlog: Gathering requirements, identifying data sources, and planning the analysis scope.
In Progress: Data cleaning, building the Python ETL pipeline, and generating visualizations.
Review/Feedback: Incorporating peer and mentor feedback.
Done: Completing the final analysis and documentation.
This Agile approach allowed me to remain flexible, making adjustments to the project when necessary, particularly after receiving feedback (linked to C7). Each sprint allowed for reflection on what was working and what needed improvement, fostering an iterative development process. Kanban was particularly useful in prioritizing tasks, managing time effectively, and meeting deadlines while maintaining a clear project structure.


Impact of Feedback and Iteration
An essential aspect of this project was the continuous integration of feedback, aligning with course goal C7. I sought input at different stages from peers with expertise in computer science, engineering, and data analysis. Their feedback helped refine both the analysis and the presentation:

I resolved the main challenge of this project based on feedback from an experienced computer scientist, and an experienced computational mechanical engineer. The major challange for th project was computation on large data using a personal computer. One dataset containing emssions data for ships is made of about a million rows and needs to be merged with an exhasutive list of ports with several thousand rows. Simply finding geographical distance between all the positions would take a lot of cimputation and virtually impossible with a PC. This required a degree of technical problem-solving to run the project on a personal computer as it was planned. I received feedback from the experts on parallel computing, and also on how to narrow down the emissions at ports through SQL queries with an arbiterary box around a geographical position in terms of lattitude and longitude (refer to the code in pipeline.py). 

I also received feedback from Industry Leader Damian Keil during the course of the project as well as in early October to help write the text that could showcase how I have achieved the course goals through running this independent project.


Evaluating Learning Needs for Professional Development
Meeting the course goal S17, I critically evaluated my learning needs throughout the project:

Data Engineering: I recognized the need to further develop my skills in handling large datasets efficiently. 
Advanced Data Visualization: I plan to expand my knowledge of interactive visualization tools like Plotly to improve the depth and presentation of future analyses.
Project Management: The use of Agile helped streamline the process, but I identified time management as an area of improvement—particularly in balancing project phases with deadlines.
This reflection enabled me to prioritize specific areas for growth and outline a roadmap for continuous professional development.







