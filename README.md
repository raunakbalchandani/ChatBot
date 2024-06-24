# ChatBot

This project implements a simple chatbot using Streamlit for handling cab-related queries. The chatbot leverages a Large Language Model (LLM) accessed through a local API to provide responses.

# Objective
The objective of this project is to develop a chatbot that helps users with cab-related queries, such as finding nearby rides and shared rides.

# Domain: Cab Services
User Base: General public needing information about cab services, including individuals looking for rides, pricing, and availability.
Scope and Type of Queries:

# Finding nearby cab services
Checking availability of shared rides
Fare estimation for different routes
General queries about cab service policies and procedures
Application Development

# Technologies Used
Streamlit: Frontend for user interface and interaction.
Python: Backend logic and integration with LLM.
Requests: Handling API requests to the LLM server.

# Setup Instructions
Clone the Repository

bash
Copy code
git clone https://github.com/your-username/cab-chatbot.git
cd cab-chatbot
Install Dependencies

bash
Copy code
pip install -r requirements.txt
Start the Streamlit App

bash
Copy code
streamlit run app.py

# Application Structure
main.py: Main Streamlit application file containing user interface and interaction logic.
requirements.txt: List of Python dependencies for easy installation.
Usage
Open the Streamlit App

Navigate to http://localhost:8501 in your web browser after starting the Streamlit app.
Enter Your Query

Type your cab-related query into the text input box provided.
Submit Query

Click the "Submit" button to see the chatbot's response.
Code Explanation
The app.py file includes:

# Initialization of Streamlit app.

Input box for users to enter queries.
Button to submit queries and display responses.
Integration with a local API (http://localhost:11434/api/generate) to fetch responses from the LLM model (driver-support-assistant).

# Example Queries

Query: "Find me a ride from Times Square to Central Park."
Query: "What are the rates for shared rides in my area?"
Query: "How can I book a cab in advance?"


# Testing Approach

Varied Queries: Test the chatbot with a range of cab-related queries to assess response accuracy and relevance.
Performance: Evaluate the speed and responsiveness of the chatbot in handling user interactions.
Usability: Gather feedback from users to improve the chatbot's interface and functionality.