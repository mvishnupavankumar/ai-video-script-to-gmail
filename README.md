# ai-video-script-to-gmail
This workflow automatically generates a 60-second video script on "today's top AI news" using the OpenRouter AI API (Mistral-7B-Instruct model) and sends it to your specified Gmail address daily at 8 AM.
✨ Features
Daily Scheduling: Triggers every day at 8 AM.

AI-Powered Script Generation: Utilizes OpenRouter's Mistral-7B-Instruct to create engaging video scripts.

Automated Email Delivery: Sends the generated script directly to your Gmail inbox.

🚀 How to Get Started
🛠️ Installation
Import the Workflow: Download the provided JSON and import it into your n8n instance.

OpenRouter API Key:

Sign up or log in to OpenRouter.

Navigate to your API Keys section.

Generate a new API key and copy it.

n8n Credentials:

In the SCRIPT node, update the Authorization header with your OpenRouter API Key in the format Bearer YOUR_API_KEY.

In the SENDING SCRIPT node, set up your Gmail OAuth2 credential. Follow the n8n documentation for Gmail OAuth2 setup.

⚙️ Configuration
Set Topic: The TOPIC node is pre-configured for "today top ai newa". You can modify this value to generate scripts on a different topic.

Recipient Email: In the SENDING SCRIPT node, change the "sendTo" email address to your desired recipient.

Schedule Time: The Schedule Trigger node is set to 8 AM daily. Adjust the triggerAtHour parameter if you want to change the delivery time.

🏃‍♀️ Usage
After importing and configuring, activate the workflow in n8n.

The workflow will automatically run daily at the scheduled time, generate an AI video script, and send it to your specified Gmail address.












Canvas


