# LLM-Based Semantic Book Recommender

## Project Description

This project implements a **Semantic Book Recommendation System** using **Large Language Models (LLM)**. The system recommends books to users based on natural language queries, leveraging pre-trained models for sentiment analysis, text classification, and vector search.

The application utilizes **Gradio** to create an interactive web interface for users to input their preferences and receive book suggestions based on semantic similarity.

## Features

- Natural language book recommendation
- Sentiment analysis for book reviews
- Text classification to categorize books
- Vector search to find books based on content similarity
- Interactive web dashboard using **Gradio**

## Technology Stack

- Python
- Hugging Face Transformers
- Gradio
- Scikit-learn
- Pandas
- Numpy
- OpenAI API

## Installation

1. Clone the repository:

   git clone https://github.com/your-github-username/llm-book-recommender.git
   cd llm-book-recommender


2. Install dependencies:
   
   pip install -r requirements.txt


3. Create a `.env` file in your root directory containing your **OpenAI API key** and Hugging Face API key:

   OPENAI_API_KEY=your_openai_api_key_here
   HUGGINGFACE_API_KEY=your_huggingface_api_key_here


4. Run the application:
  
   pyhton Book-recommender.py


5. Access the app at `http://localhost:7860`

## Folder Structure

.
├── data-exploration.ipynb    # Data exploration notebook
├── Book-recommender.py       # Web interface with Gradio
├── semantic-sentiment.ipynb   # Sentiment analysis module
├── text-classification.ipynb  # Text classification module
├── vector-search.ipynb       # Vector search and book recommendations
└── requirements.txt          # Required libraries


## Hugging Face API

The system leverages pre-trained models from **Hugging Face Transformers** to perform text classification and sentiment analysis. To access the models, you'll need to generate an API key from Hugging Face's website.

1. Go to [Hugging Face](https://huggingface.co/)
2. Create an account or log in.
3. Navigate to your **Settings** and generate an **API token**.
4. Add your token to the `.env` file as `HUGGINGFACE_API_KEY`.

Documentation: [Hugging Face Transformers](https://huggingface.co/docs/transformers/)

## Usage

1. Open the application.
2. Enter a book topic or description in the input box.
3. Click the **Recommend Books** button.
4. The system will display the top book recommendations based on semantic similarity.

## Contribution

Feel free to fork this repository and enhance the recommendation system with additional features.

## Author

**Chirag S. Shetty**\
Email: [chiragsshetty17@gmail.com](mailto:chiragsshetty17@gmail.com)\


## License

This project is licensed under the MIT License.

