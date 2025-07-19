Custom AI Recipe Generator
Overview
Ever stared into your fridge, wondering what delicious meal you can whip up with the ingredients you actually have on hand? Say goodbye to food waste and recipe hunting headaches!

This Custom AI Recipe Generator is your personal culinary assistant, powered by cutting-edge Generative AI. Simply tell it what ingredients you have available, and watch as it instantly crafts a unique, exciting recipe just for you.

Features
Intelligent & Personalized Recipes: The AI analyzes your precise ingredients to generate a custom recipe tailored to what's in your pantry.

Creative & Fun Names: Each recipe comes with a delightful, unique name, often accompanied by a humorous alternative.

Clear, Step-by-Step Instructions: Follow along with easy-to-understand directions, making even complex dishes approachable.

Surprising Fun Facts: Learn something new and interesting about your meal or ingredients with a fun fact included at the end of every recipe.

Reduce Food Waste: Maximize your groceries by getting creative ideas for ingredients you might otherwise overlook.

Effortless to Use: With a clean, intuitive web interface, generating your next meal is just a few clicks away.

Setup and Installation
To run this application, you'll need Python installed on your system.

Clone the repository (or save the code):
If you have the code in a file (e.g., app.py), save it.

Create a Virtual Environment (Recommended):

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install Dependencies:
Install the required Python packages using the requirements.txt file provided.

pip install -r requirements.txt

Set Up OpenAI API Key:
The application requires an OpenAI API key. You need to set this as an environment variable.

export OPENAI_API_KEY='your_openai_api_key_here'
# On Windows (Command Prompt): set OPENAI_API_KEY=your_openai_api_key_here
# On Windows (PowerShell): $env:OPENAI_API_KEY='your_openai_api_key_here'

Replace 'your_openai_api_key_here' with your actual OpenAI API key.

How to Run
After setting up the environment and API key, run the Flask application:

python app.py

The application will typically run on http://0.0.0.0:8080/. Open your web browser and navigate to this address.

Usage
Enter Ingredients: On the web page, you'll find an input field labeled "Ingredients / Items:". Enter a comma-separated list of ingredients you have (e.g., "Bread, jam, potato").

Generate Recipe: Click the "Share with me a tutorial" button. The application will use Generative AI to create a recipe based on your input.

View and Copy Output: The generated recipe, including its name, funny name, step-by-step instructions, and a fun fact, will appear in the "Output" section. You can use the "Copy" button to easily copy the text to your clipboard.

Enjoy your custom-generated recipes!
