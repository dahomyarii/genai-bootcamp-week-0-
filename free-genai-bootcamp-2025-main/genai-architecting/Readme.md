Functional Requirements
The platform should provide personalized career guidance based on AI-driven analysis of user inputs.
The company wants to host its own infrastructure to maintain control over data privacy and avoid vendor lock-in.
The AI system should support 500 active users, primarily students and career advisors, within the city of Kyoto.
The system must integrate with external job market APIs (e.g., LinkedIn, Indeed) for real-time job postings.
The company has a budget of $20K for setting up AI infrastructure, including hardware, storage, and security measures.
Assumptions
We assume that open-source LLMs will be powerful enough to provide accurate and useful career recommendations.
The system will be hosted on-premises, with a dedicated AI server, and will have enough bandwidth to support all active users.
The platform’s recommendation system will be effective in suggesting career paths based on user input and market trends.
Data Strategy
The database should include career skills, industry trends, job market insights, and user profiles.
User data should be encrypted to ensure privacy and compliance with data protection regulations.
The system should avoid copyrighted job-related materials by relying only on public datasets and purchased career guidance reports.
Considerations
Considering IBM Granite or Mistral AI as the foundational LLM, as they provide transparency in training data and avoid copyright risks.
The recommendation model should be fine-tuned with local job market data to improve relevance for users in Kyoto.
Since the company wants a cost-effective solution, hybrid cloud deployment (on-prem + cloud backup) should be explored to optimize expenses.
Implementing monitoring and feedback loops to refine career recommendations over time based on user interactions.