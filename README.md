# Virtual Research Assistant

The **Virtual Research Assistant** is a cutting-edge AI-powered tool designed to assist researchers and students in streamlining their research process. It leverages Groq-powered models to fetch, summarize, and analyze research papers with ease.

---

## Features

- **📚 Fetch Research Papers**: Retrieves relevant papers from ArXiv and Google Scholar based on user queries.
- **📝 Summarization**: Provides concise and relevant summaries of research papers using DeepSeek models.
- **🔍 Analysis**: Highlights the advantages and disadvantages of research papers in a structured format.
- **⚡ Efficiency**: Streamlines the research workflow with quick, actionable insights.

---

## Setup and Installation

Follow these steps to set up and run the project:

### 1. Clone the Repository
First, clone the repository to your local machine by running the following commands in your terminal:

```bash
git clone https://github.com/Ankita-Codee/End-to-End-Virtual-Research-Assistant
cd End-to-End-Virtual-Research-Assistant
```

### 2. Install Dependencies
1. Ensure that Python 3.10 or later is installed. You can check this by running:
```bash
python --version
```
2. After ensuring that Python is installed, install the required dependencies by running:
```bash
pip install -r requirements.txt
```
This will install all the necessary libraries needed for the application.

### 3. Set Environment Variables
Create a `.env` file in the project directory and add your Groq API key to it. This key is required for interacting with the Groq-powered models.

In your project folder, create a file named `.env`.

Add the following line to the `.env` file:

```ini
GROQ_API_KEY=your_groq_api_key
```
Make sure to replace your_groq_api_key with the actual API key you received.

### 4. Run the Application
Once the dependencies are installed and the environment variables are set, you can start the application by running the following command:

```bash
streamlit run app.py
```

### 5. Access the Application
After running the application, open your web browser and navigate to:

```bash
http://localhost:8501
```

### 6. Acknowledgements
- **Groq**: For providing the AI-powered models used in this project.
- **Streamlit**: For making it easy to build and share interactive web apps.
- **Sunny Savita**: For providing valuable insights and resources. You can check out their YouTube channel [Sunny Savita YouTube Channel](https://www.youtube.com/@sunnysavita10).
