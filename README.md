# crisis-mental-health-agent

A supportive mental health assessment and guidance system powered by AG2(formerly AutoGen)'s AI Agent framework. This app provides personalized mental health support through the coordination of specialized AI agents, each focusing on different aspects of mental health care based on user inputs such as emotional state, stress levels, sleep patterns, and current symptoms. This is built on AG2's new swarm feature run through initiate_swarm_chat() method.

Specialized Mental Wellbeing Support Team:
🧠 Assessment Agent: Analyzes emotional state and psychological needs with clinical precision and empathy
🎯 Action Agent: Creates immediate action plans and connects users with appropriate resources
🔄 Follow-up Agent: Designs long-term support strategies and prevention plans

How to Run
Follow these steps to set up and run the application:

Clone the Repository:

git clone https://github.com/Shubhamsaboo/awesome-llm-apps.git
cd advanced_ai_agents/multi_agent_apps/ai_mental_wellbeing_agent
Install Dependencies:

pip install -r requirements.txt
Create Environment File: Create a .env file in the project directory:

echo "AUTOGEN_USE_DOCKER=0" > .env
This disables Docker requirement for code execution in AutoGen.

Set Up OpenAI API Key:

Obtain an OpenAI API key from OpenAI's platform
You'll input this key in the app's sidebar when running
Run the Streamlit App:

streamlit run ai_mental_wellbeing_agent.py
