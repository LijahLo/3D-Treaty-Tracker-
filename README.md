# 3D-Treaty-Tracker-
This project is a web application that will select countries base off each peace treaty. Treaty Compass transforms complex international law into a visual, data-driven experience. Users can explore countries on an interactive map, select a treaty, and instantly receive an supporting insights from global sources.
Our project addresses the gap between international human rights agreements and real-world enforcement. While many countries sign treaties like CEDAW, ICCPR, and CRC, it is often unclear how well they actually comply with them. The information exists, but it is scattered across long reports, legal documents, and multiple organizations, making it difficult for everyday users to access and understand.We chose this issue because of its global relevance and lack of accessibility. Human rights impact everyone, but the systems used to track them are not designed for public understanding. We wanted to create a tool that simplifies this complexity and makes global accountability more transparent.
Research showed us that:

Data is fragmented across UN, NGO, and news sources
Reports are dense and not user-friendly
There is no centralized, interactive platform for comparison

This led us to design a solution that aggregates insights, simplifies them using AI, and presents them visually through a map interface.

Our project allows users to select a country and treaty,  view categorized gaps (critical, partial, strong), and access supporting insights from global sources. It transforms static legal data into a real-time, interactive experience.

We combine AI with geospatial visualization
We provide instant summaries instead of long reports
We unify multiple data sources into one interface
We prioritize accessibility over technical complexity

Most existing tools are either academic databases or static dashboards. Our project is interactive, intuitive, and real-time.

The system successfully generates structured outputs, including scores and categorized gaps, using real-world data sources. Users can interpret complex treaty compliance within seconds. The outputs align with patterns found in established reports from global organizations. The architecture also allows for scalability, additional data integration, and improved accuracy over time.

How did you build your project?

We built the project as a full-stack application:

Frontend: Interactive map (Leaflet/D3), UI panels, user input
Backend: Express API for handling requests and security
AI Integration: Anthropic API for analysis and structured outputs

The system connects user interaction to backend processing, AI analysis, and visual output.


We chose JavaScript across the stack for consistency and efficiency. Leaflet and D3 were selected for flexible and powerful map visualization. Node.js and Express provide lightweight and scalable backend support. The Anthropic API was chosen for its ability to produce structured, explainable outputs. This combination allowed us to build quickly while maintaining scalability.

What challenges did you face?
Converting unstructured AI responses into clean, usable JSON
Matching country names across different datasets
Deciding between Leaflet and D3 for map rendering
Securing API keys by moving logic to the backend
Keeping the interface simple while handling complex data
In the future, how would you face these challenges differently?
Implement stricter validation for AI responses
Use standardized datasets for country naming
Finalize architecture decisions earlier in development
Introduce caching to reduce repeated API calls
What did you learn?
How to integrate AI into a real-world application beyond basic chat use
The importance of data structure and validation
How to design user interfaces for complex information
How frontend and backend systems must work together effectively
How can you further your learning from this project?
Explore data pipelines and API integration
Improve prompt engineering and AI evaluation methods
Study advanced data visualization techniques
Learn more about global policy and data ethics
What’s next for your project?
Color-coded map based on compliance scores
Full country coverage with automated data
Search and filtering features
Report export functionality
Deployment to a live platform
Why is your project’s next step what it is?

The next steps focus on improving usability, expanding data coverage, and making the tool more actionable. These improvements move the project from a prototype toward a production-ready system.

If you used any AI tools, where and how did you use them?

The AI tools that weree used was ChatGPT and Deepseek, These tools was used in two primary ways:

Backend Analysis
The AI processes real-world data from UN reports, NGOs, and news sources to generate structured outputs, including compliance scores and gap analysis.
Development Support
AI assisted with debugging, structuring code, refining architecture, and improving user interface design.

AI was used as a tool to enhance both development and functionality, while maintaining human oversight and decision-making.
