# Shipping Emissions at Port

Using anonymised vessel emissions data from the NGO Transport & Environment, I built a pipeline in Python to present an analysis on shipping emissions at port, addressing questions raised by the NGO.  
The data includes hourly entries for carbon emissions, and geographical coordinates for 100 unique container ships.

![World map emissions](/media/port_emissions_map.png "Emissions at Port")

## Purpose and Analysis
The aim of this project was to explore the environmental impact of container ships when stationed at port, where emission levels have health implications as well as climate impact. Emissions at ports are interesting to measure as they can be mitigated through the use of shore power. By identifying key patterns and offering actionable insights, this analysis provides information to the general public, legislators, and other stakeholders on port emissions and how to reduce them. These include:

I was asked by the NGO Transport & Environment to find policy-relevant insights on emissions at European ports and explore the data for other insights that could be relevant to the general public or policymakers. North Sea ports of Hoek von Holland, Bremerhaven, and Felixstowe had the highest share of emissions due to congestion and long waiting times, raising public health concerns as these ports are near populated urban areas. These results are relevant for city and regional planners, among other stakeholders.

The results show that 4% of global emissions from the container sector occur at ports. This percentage could theoretically be reduced to zero with the introduction and diffusion of shore-side electricity, allowing vessels to shut down their engines and stop emissions while at port.  
Additionally, the analysis revealed significantly higher rates of greenhouse gas emissions in African ports, which is alarming and calls for scrutiny beyond national legislation.

This analysis aligns with course goal **S16**: to run an industry-relevant project showcasing my analytical and reflective capabilities. This topic is timely within the maritime industry. The project uses anonymised real data, handled and shared by the NGO Transport & Environment in compliance with all relevant regulatory requirements.  
I cleaned, organized, transformed, and analyzed the data, and presented the results to the NGO. The results included a Jupyter notebook containing an interactive map visualizing global emissions at port, a slide deck, and an accompanying report offering data-driven recommendations for reducing carbon footprints.

## Independent Project Execution and Management
As part of achieving **S16**, I used Agile project management practices to structure my work. I broke down the project into smaller tasks using a Kanban board, ensuring steady progress:

- **Backlog:** Gathering requirements, identifying data sources, and planning the analysis scope.
- **In Progress:** Data cleaning, building the Python ETL pipeline, and generating visualizations.
- **Review/Feedback:** Incorporating peer and mentor feedback.
- **Done:** Completing the final analysis and documentation.

This Agile approach allowed me to remain flexible, making adjustments to the project when necessary, particularly after receiving feedback (linked to **C7**). Each sprint allowed for reflection on what was working and what needed improvement, fostering an iterative development process. Kanban was particularly useful in prioritizing tasks, managing time effectively, and meeting deadlines while maintaining a clear project structure.

## Impact of Feedback and Iteration
An essential aspect of this project was the continuous integration of feedback, aligning with course goal **C7**. I sought input at different stages from peers with expertise in computer science, engineering, and data analysis. Their feedback helped refine both the analysis and the presentation:

I resolved the main challenge of this project based on feedback from an experienced computer scientist and a computational mechanical engineer. The major challenge was performing computations on large datasets using a personal computer. One dataset, containing emissions data for ships, consisted of about a million rows and needed to be merged with an exhaustive list of ports, which had several thousand rows. Simply calculating the geographical distance between all positions would have required an immense amount of computation, making it nearly impossible to run on a PC. I applied the feedback from experts on parallel computing and also used SQL queries with an arbitrary box around a geographical position (latitude and longitude) to narrow down the emissions data at ports (refer to `pipeline.py`).

I also received feedback from industry leader Damian Keil during the project, which helped me craft the text that showcases how I achieved the course goals through running this independent project.

## Evaluating Learning Needs for Professional Development
Meeting course goal **S17**, I critically evaluated my learning needs throughout the project:

- **Data Engineering:** I recognized the need to further develop my skills in handling large datasets efficiently.
- **Advanced Data Visualization:** I plan to expand my knowledge of interactive visualization tools like Plotly to improve the depth and presentation of future analyses.
- **Project Management:** The use of Agile helped streamline the process, but I identified time management as an area of improvement—particularly in balancing project phases with deadlines.

This reflection enabled me to prioritize specific areas for growth and outline a roadmap for continuous professional development.
