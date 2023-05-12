# TMD-Final-Project
# Election Monitoring and Disinformation: A Comprehensive Data Analysis Report
# Tech, Media, and Democracy

Akhil Uddandam (ECE) | Rohit George (MBA) |Purushottam Chandra (MBA) | Grace Liu (ORIE) | Jigar Jain (MBA) | Rahul Rai (MBA)


# Introduction
Misinformation poses a significant challenge to democracy, particularly in US politics. Our big idea is to address this problem by utilizing the Google Fact Checker tool as a primary source of information. The tool helps combat misinformation by providing fact-checking information from credible sources and  using a rating system to indicate the accuracy of claims. By exploring data and trends related to misinformation in US politics, we aim to promote informed public discourse and highlight the prevalence and impact of misinformation. Our working system, a dashboard that provides access to accurate information about representatives' statements, can be found at Click link.

# Overview of the system/prototype/plan’s main features
The system prototype is an innovative and user-friendly dashboard that empowers voters with valuable insights. One of its primary features is the provision of information regarding the average accuracy of representatives' statements. This transparency allows voters to gauge the credibility of their elected officials, enabling them to make informed decisions. 
Additionally, the prototype employs a visually engaging heatmap to present information effectively. This dynamic visualization tool enables users to filter and explore critical topics like healthcare, immigration, climate change, taxes, gun control, and abortion. By offering this comprehensive view, the dashboard facilitates a deeper understanding of politicians' positions on these crucial issues. 
To ensure the accuracy and reliability of data, the prototype collects information from various sources, including social media posts, public statements, and claims made during debates. This comprehensive approach equips voters with the necessary information to hold politicians accountable during election seasons. 
To present these insights in a user-friendly manner, the prototype leverages the powerful visualization capabilities of the Tableau platform. Tableau enables interactive and intuitive visualizations, making it easier for users to navigate and comprehend complex data. 
Overall, this system prototype's dashboard combines accessibility, transparency, and visual appeal to enhance voters' engagement and understanding of political matters. By leveraging data from multiple sources and utilizing Tableau's visualizations, the prototype facilitates informed decision-making and empowers voters to play an active role in holding politicians accountable.

# Technical aspects of the final implementation
The technical aspects of the final implementation involve several key components. Firstly, the implementation relies on the Google Fact Checker tool as the primary data source. This tool aggregates fact-checking information from reputable sources, including PolitiFact, FactCheck.org, and The Washington Post. By leveraging this tool, the system can access a wide range of credible information to analyze and identify trends in misinformation. The end-to-end data flow can be seen in the below system diagram:

Data analysis plays a crucial role in the implementation. The collected data from the Google Fact Checker tool is analyzed to extract insights and identify patterns of misinformation. This analysis helps in understanding the prevalence of misinformation related to the selected topics, such as healthcare, immigration, climate change, taxes, gun control, and abortion. 
For sourcing the candidate information, we used the Federal Election Commission website which has a comprehensive list of candidates along with other details suc. We extracted the names and their con
To provide a user-friendly interface and visualize the analyzed data, the implementation utilizes Tableau. Tableau allows for the creation of interactive visualizations, including heatmaps, that enable users to explore the accuracy of representatives' statements and filter information based on specific topics. 
To visualize the data, a left join between the extracted insights of selected topics and the l

To ensure comprehensive coverage, the implementation incorporates data collection from representatives' various communication channels, such as social media posts, public statements, and claims made in debates. This data collection process involves scraping and aggregating relevant information from these sources, enabling the system to provide a holistic view of representatives' statements and actions. 
Overall, the technical implementation combines data aggregation from the Google Fact Checker tool, data analysis to identify trends in misinformation, data visualization using Tableau, and comprehensive data collection from representatives' communication channels. These technical components work together to create an informative and user-friendly system that helps combat misinformation and holds politicians accountable during election seasons.

# Key technical challenges addressed
The key technical challenges addressed in the implementation were significant and required careful consideration. One of the primary challenges was the reliance on third-party data sources and human-based fact-checking, which inherently limited scalability. To address this challenge, we leveraged the Google Fact Checker tool, which aggregates fact-checking information from multiple credible sources. By utilizing this tool, we were able to access a broader range of data and mitigate scalability limitations. 
Another challenge was the variations in fact-checking organizations, which made it challenging to compare and consolidate information across different sources. To overcome this, we adopted an approach that relied on aggregated data from multiple reputable fact-checking sources. By considering information from various sources, we aimed to provide a comprehensive and balanced view of the accuracy of political claims. 
The development of the dashboard prototype also presented technical challenges. It required expertise in data analysis to process and extract meaningful insights from the data collected. Additionally, data visualization skills using Tableau were necessary to create interactive and visually appealing representations of the information. Integration of different data streams, including social media posts, public statements, and debate claims, further added complexity to the implementation. 
By successfully addressing these challenges, we were able to develop a robust system that provides users with reliable and accessible information to combat misinformation and enhance accountability during election seasons

# The theory of change and plausibility of your contribution
Through the analysis of data related to misinformation and the promotion of fact-checking tools like Google Fact Checker, our contribution aims to have a positive impact on combating misinformation in US politics. The theory of change behind our approach is rooted in the belief that transparency, accuracy, and media literacy are key factors in mitigating the spread of misinformation. By providing voters with access to accurate information about their representatives' statements, we empower them to make informed decisions and engage in more meaningful public discourse. 
While our current prototype has its limitations and areas for improvement, the plausibility of our contribution lies in its potential for refinement and expansion. Future directions could involve developing more sophisticated methods for detecting and categorizing false information, conducting research on effective interventions to counter misinformation, and enhancing the system's scalability and data sources. By addressing these aspects, we can further strengthen the system's ability to combat misinformation in a more comprehensive and impactful manner. 
It is important to recognize that addressing misinformation is a complex challenge that requires a multi-faceted approach. Our contribution aligns with the ongoing need for improvements in the electoral process, media literacy, and continuous research efforts. By focusing on these areas and working towards refining our system, we contribute to the broader goals of promoting transparency, accuracy, and informed decision-making in US politics

# A list of collaborators and a statement of contribution (1-2 sentences) from each participant, reflecting their contribution to the project
Our research project is a collaborative effort between the following individuals:
Akhil & Puru are responsible for conducting literature reviews and analyzing data related to digital media's role in election monitoring
Grace & Rohit are responsible for researching and analyzing issues and best practices related to the use of technology in elections
Rahul is responsible for investigating the relationship between the electoral process and democracy
Jigar is responsible for coordinating communication and ensuring that the project stays on track

