# Intern_multiagent_system
#Overview
The Smart City Delivery Simulation is an interactive tool that demonstrates how AI agents can collaborate to optimize urban delivery logistics. The system uses a combination of planning, navigation, and execution agents to simulate real-world delivery scenarios in a dynamically generated city environment.
Key Features

🗺️ Dynamic City Generation: Creates random city layouts with buildings, rivers, and bridges
🤖 AI-Powered Agents: Three specialized AI agents working together:

Chief Planning Officer (CPO): Strategic delivery operations director
Master Navigator: Geospatial intelligence and route optimization specialist
Elite Courier: Field operations delivery specialist


📊 Visual Simulation: Real-time visualization of city map and delivery routes
🚀 Interactive UI: User-friendly Gradio interface to run and monitor simulations

#Technology Stack

Python 3.7+
CrewAI for multi-agent orchestration
OpenAI API for agent intelligence
Matplotlib for visualization
Gradio for the web interface
NumPy for numerical operations


#Using the Interface

With API Key: Enter your OpenAI API key in the provided field and click "Run Simulation" to experience the full AI-powered simulation.
Demo Mode: Click "Demo Mode (No API Key)" to run the simulation with pre-defined paths and decisions.
Simulation Output: The interface will display:

Progress log showing real-time simulation status
Initial city map visualization
Final delivery routes visualization
Statistics on successful and failed deliveries



#Requirements
Create a requirements.txt file with the following dependencies:
numpy
matplotlib
gradio
crewai
requests
langchain
openai
