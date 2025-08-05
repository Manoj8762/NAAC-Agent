Building an AI Agent for NAAC using IBM Cloud (WatsonX)
Step 1: Access IBM Cloud
Open your browser and go to: https://cloud.ibm.com.

If you don’t have an IBM Cloud account, create a new account.

Step 2: Access WatsonX Platform
In the IBM Cloud search bar, type "watsonx".

On the left sidebar, click on “watsonx.ai”.

Select "GEN AI Solutions".

Click on "Automating Tasks with AI Agents".

Click on "Agent Lab (Beta)".

Step 3: Create a New Project
Scroll down and click on “WatsonX.ai Home Page”.

In the new page, at the bottom, click "+" > "New Project".

Provide a Project Name.

Click "Add" and "Create" cloud storage (choose the free option if applicable).

Click “Refresh” and then “Create”.

Step 4: Build an AI Agent
From the left navigation bar, select "Build an Agent to Automate Tasks".

Click on "Manage" > "Service & Integration".

Click on "Associate Service".

Create a new service named "watsonx.ai runtime", tick the checkbox, and click "Associate Service".

Return to Home from the left navigation bar.

Step 5: Configure Your Agent
Go to "Build an Agent to Automate Tasks" again.

Click "Setup" and provide your Agent Name.

Under Model, select "IBM Granite-3-3-Instruct".

On the right-hand configuration panel, set:

Frequency Penalty: 1.5

Presence Penalty: 1.7

Random Seed: 42

Stop Sequences: Define where you want the generation to stop.

Under Instructions, provide:

Agent Instructions (specific to NAAC task handling)

Common Instructions (general task behavior)

Click "Apply".

Step 6: Add Knowledge & Tools (Optional)
If you have supporting documents, upload them under "Knowledge".

Add any additional tools if required.

Step 7: Preview & Save the Agent
Click on "Preview" to test the agent with sample queries.

Once satisfied, click "Save as Agent".

Name your agent and create a New Deployment Space.

Step 8: Deploy the Agent
Select Production Environment.

Choose watsonx runtime and click "Go to Space".

From the left navigation bar, go to "Automating Tasks with AI Agents".

You’ll see your saved agent (marked with a human head tag).

Click on the agent, select "Edit", and then click "Deploy".

A deployment initialization message will appear, indicating the agent is active.

Step 9: Save as Notebook (Optional)
To save your AI Agent as a Notebook:

Go to Home > Build an Agent to Automate Tasks.

Find your saved agent (with the human head icon).

Click "Save As".

Choose "Save as Standard Notebook".

To export the notebook:

Navigate back to your project.

Use the Export/Import option at the top of the page.
