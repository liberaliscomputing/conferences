# Response to Reviewer Feedback on 'Empowering Library Services through User-Centric Analysis of Co-loan Patterns'

## Reviewer 1

### **Could the author further expound on the term _co-loan_ in the introduction?**

- The term _co-loan_ refers to a situation where multiple books are borrowed by a single user on the same day, forming a set of co-loaned items. Analyzing _co-loan_ patterns allows us to understand how users group books in a single borrowing session, potentially revealing their thematic or subject preferences. This is particularly useful for libraries, as it highlights the relationships users see between books, which may differ from traditional library classification systems. Libraries can leverage this insight for improving collection organization, personalized recommendations, and shelf arrangements, all based on actual user behavior.

### **Was the loan data anonymized since the dataset contains userID?**

- Yes, the loan data was anonymized to protect user privacy. While the dataset included user IDs, these identifiers were pseudonymized to ensure confidentiality, meaning no personally identifiable information was accessible to researchers. This approach complies with data privacy standards and allows for the safe analysis of borrowing patterns without infringing on users' privacy rights.

### **What could be the reason for the high inclination towards literature?**

- The dominant borrowing of literature can be linked to several factors. First, literary works are often central to education, with students and academics frequently turning to libraries for access to such materials. Additionally, public interest in fiction, novels, and other literary genres may drive the high demand for these books. In South Korea, literature plays a significant role culturally, both for academic use and recreational reading, which likely explains its high borrowing rates.

### **How does the _co-loan_ concept relate to user behavior and how might it be useful for library decision-making?**

- The _co-loan_ analysis provides valuable insights into user behavior by revealing patterns in how patrons group books during a single library visit. These patterns reflect the information needs and interests of users in real-time, offering actionable data for libraries. For example, if users consistently borrow books on similar topics together, libraries can group those books more effectively in their physical and digital collections. It also aids in refining recommendation systems by predicting which topics or genres a user might want to explore next, based on prior borrowing habits.

### **Were there any potential biases or limitations in the data, such as the overwhelming inclination toward literature, that might affect generalizability?**

- The overwhelming preference for literature may introduce certain biases into the findings. It might suggest that other categories, such as science or arts, are underrepresented, potentially skewing the analysis of co-loan patterns. The strong inclination toward literature could reflect South Korea's cultural or educational trends, but may not fully represent the diversity of users' interests. Additionally, the high volume of literature-related loans may overshadow more niche genres, making it difficult to generalize findings across different subjects. Future research could address this limitation by conducting comparative studies across more balanced subject areas or adjusting the dataset to normalize category representation.

## Reviewer 2

### **Please provide a definition for what is meant by _co-loan_ data in relation to user-needs?**

- _Co-loan_ data refers to the set of books borrowed by a user during the same loan transaction. In the context of user needs, _co-loan_ patterns help libraries understand the thematic or subject-based connections between borrowed books, revealing user preferences. This understanding aids in aligning library collections more closely with actual user behaviors, thereby enhancing collection management, personalized recommendations, and strategic resource planning.

### **Is this to help develop resource planning?**

- Yes, the analysis of _co-loan_ data is highly relevant for resource planning. By identifying which subjects or genres are frequently borrowed together, libraries can better curate collections, optimize shelving arrangements, and ensure that related materials are easily accessible to patrons. This approach supports the overall goal of improving user satisfaction and library efficiency by making data-driven decisions on resource allocation.

### **What precisely is this study's contribution to supporting library collection development?**

- The study offers actionable insights for library collection development by revealing the actual borrowing patterns of users, which may differ from traditional classification schemes. Libraries can use these insights to fine-tune their collection strategies, prioritizing books that are frequently co-loaned and ensuring that related subjects are readily available. Additionally, understanding user preferences through _co-loan_ data enables libraries to develop more personalized services, such as targeted recommendations, ultimately fostering a more user-centered approach to collection development.

### **What are the limits to such forms of predictive modeling?**

- One limitation of predictive modeling based on _co-loan_ data is the potential oversimplification of user behavior. Users may borrow books together for reasons that are not necessarily thematic (e.g., convenience, browsing habits). Furthermore, while predictive models can highlight popular trends, they may overlook the needs of outliers or minority groups whose borrowing patterns deviate from the mainstream. Libraries must be cautious not to overly rely on these models, ensuring that they remain responsive to diverse user needs and preferences.

### **Who might be left out of such classification schemes?**

- Users whose borrowing habits do not align with the majority may be marginalized by classification schemes driven by _co-loan_ patterns. For instance, readers who explore niche topics or unconventional combinations of books might not benefit from collection adjustments or recommendations optimized for more common patterns. Libraries should consider these outliers and ensure that their needs are met, perhaps by offering additional support or promoting less popular subjects alongside more frequently borrowed materials.

### **Do the outliers of the pattern no longer receive the resources they need if applying this model?**

- While the model focuses on majority borrowing patterns, outliers are not necessarily deprived of resources. However, there is a risk that libraries might prioritize popular subjects at the expense of niche areas. To mitigate this, libraries should adopt a balanced approach, using _co-loan_ data to improve mainstream services while also maintaining a diverse and inclusive collection that caters to less common needs.

## Reviewer 3

### **Can you clarify the use of GenAI for labeling the communities?**

- We used a proprietary large language model (GPT-4 Turbo) to assist with labeling the detected communities. By analyzing the top 30 subjects in each community, their frequencies, and network centrality metrics, the model generated descriptive labels. This method allowed us to process large datasets efficiently and generate meaningful labels based on observed patterns. The use of GenAI, in this context, helps streamline the process of labeling while ensuring consistency across a large volume of data.

### **Is using GenAI an acceptable research method for labeling communities?**

- Yes, using GenAI is increasingly accepted in research, particularly when dealing with large and complex datasets. In our study, the model’s role was to enhance efficiency in labeling communities, providing consistency and scalability. The process was supervised to ensure the labels accurately represented the data, thus maintaining research integrity while leveraging advanced technology.

### **What were the criteria for selecting the prominent user communities (Global Modern Literature and Novels; Children’s Literature, Fairy Tales, and Folklore)?**

- The selection of prominent communities was based on the centrality of the subjects within the co-loan network, as well as their frequency of occurrence in the dataset. Communities like "Global Modern Literature and Novels" and "Children’s Literature, Fairy Tales, and Folklore" were identified as central due to their high borrowing rates and their strong connections to other subject areas. These communities represent the dominant reading interests within the dataset, making them significant for further analysis.

### **Were there any potential biases in the GenAI labeling process?**

- While GenAI helps streamline the labeling process, there is potential for bias, especially when the training data of the model may influence the labels. To mitigate this, we provided specific inputs (top subjects and centrality measures) and reviewed the model's output to ensure that the generated labels accurately reflected the underlying data. However, there remains a need for human oversight to ensure that the labels are contextually appropriate and free from unintended biases.

### **Does the use of GenAI add practical value to the research, particularly for libraries?**

- Yes, the use of GenAI adds significant practical value, particularly in processing large datasets like ours. For libraries, the ability to rapidly analyze and categorize user behavior into meaningful communities can inform more personalized services, such as tailored book recommendations and improved collection management. GenAI enhances the scalability of such tasks, allowing libraries to handle large and complex datasets efficiently, which would otherwise be time-consuming using traditional methods.

## Floor

### **How can libraries foster a sense of belonging and community among their patrons?**

- Libraries can foster a sense of belonging and community by creating spaces and services that reflect the diverse interests and needs of their patrons. Based on our study, libraries can use insights from _co-loan_ patterns to curate community-driven collections that resonate with users' preferences. Additionally, libraries could host events, book clubs, or discussions based on the prominent themes identified in their data, providing opportunities for patrons to engage with each other over shared interests. By aligning services and programming with user behavior, libraries can create an environment where patrons feel seen, understood, and connected to both the institution and their peers.

### **Can personalized recommendations based on co-loan patterns contribute to fostering community?**

- Yes, personalized recommendations based on _co-loan_ patterns can contribute significantly to fostering community. When users are presented with suggestions that reflect not only their individual preferences but also the interests of others within their community, it can spark shared experiences and discussions. This personalized engagement encourages interaction between patrons, either directly (through community events) or indirectly (through shared reading materials), promoting a sense of belonging within the library’s user base.

### **How can libraries ensure inclusivity while fostering a sense of community, considering that some users may have niche or less popular interests?**

- To ensure inclusivity, libraries should balance their focus on majority borrowing trends with efforts to support niche interests. While _co-loan_ patterns can guide mainstream collection development, libraries must also actively promote diverse and lesser-known genres. This can be done through targeted outreach, curated collections for underrepresented topics, and spaces that encourage exploration beyond popular themes. By offering diverse programming and resources, libraries can ensure that every patron, regardless of their interests, feels welcome and part of the community.

