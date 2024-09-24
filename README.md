# WebSeriesSuggester
**WebSeriesSuggester** is an AI-powered chatbot designed to recommend the best web series to users based on their preferences, mood, and viewing history. Leveraging a large language model (LLM), this chatbot assists users in discovering new content across genres, platforms, and regions. It provides suggestions that are tailored to the user's taste, ensuring an enjoyable viewing experience.

**Features**
User-friendly Interface: Receive web series recommendations through simple and intuitive interaction.
Comprehensive Web Series Database: Covers various genres (Action, Comedy, Drama, Sci-Fi, etc.), platforms (Netflix, Amazon Prime, Disney+, and more), and languages to provide diverse suggestions.
Personalized Recommendations: Offers tailored suggestions based on user input, including preferred genres, languages, platforms, mood, and past viewing habits.
Dynamic Interaction: Engages users with interactive and adaptive suggestions, adjusting based on user preferences and feedback.
Multi-Platform Support: Provides suggestions available on multiple streaming platforms, ensuring accessibility across user subscriptions.
In-depth Reviews and Summaries: Supplies brief descriptions, ratings, and reviews of each recommended web series to help users make informed decisions.

**Installation**
To get started with WebSeriesSuggester, follow these steps:

Clone the Repository
git clone https://github.com/VikasMansighka/WebSeriesSuggester.git
cd WebSeriesSuggester

Install the Gaia Node: Run the following command to install the necessary node:
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash

Update the Config File: Set the configuration to run with a suitable language model by executing:
gaianet init --config https://raw.githubusercontent.com/harishkotra/Gaia-8G/refs/heads/main/config_8g.json

Start the Node: Once the setup is complete, start the node with:
gaianet start

**How to Use**
Access the Interface
Open your web browser and navigate to the link generated after starting the WebSeriesSuggester. The chatbot will be available on a local or cloud-hosted interface.

**Interact with the Chatbot**
Start the conversation by providing details such as your preferred genre, the platform you use, or even your current mood. The chatbot will analyze your preferences and provide a list of web series tailored to your interests.

**Example Interactions**
User: "Can you recommend a good sci-fi series available on Netflix?"

Chatbot: "Sure! You might enjoy Stranger Things. It’s a mix of sci-fi, horror, and thriller with a nostalgic 80s vibe. It’s available on Netflix."

User: "I’m looking for a comedy series in English. Any suggestions?"

Chatbot: "How about The Office? It's a hilarious mockumentary-style sitcom about a mundane office environment. You can find it on Peacock."

