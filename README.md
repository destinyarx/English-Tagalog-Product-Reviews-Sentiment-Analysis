# Product Review Sentiment Analysis

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Django](https://img.shields.io/badge/Django-3.2%2B-green)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0%2B-orange)

## Overview

This web application performs sentiment analysis on product reviews in both Tagalog and English languages. It utilizes a Convolutional Neural Network (CNN) model trained on a dataset consisting of 6,300 training samples and 2,700 testing samples. The data for training and testing was collected by web scraping an e-commerce website using Selenium.

## Features

- Sentiment analysis for product reviews.
- Support for both Tagalog and English languages.
- Utilizes a CNN model for accurate sentiment classification.
- Easy-to-use web interface for inputting reviews and obtaining sentiment analysis results.

## Technologies Used

- Python
- Django
- TensorFlow
- Selenium

## Installation

To run this application locally, follow these steps:

1. Clone the repository: `git clone https://github.com/yourusername/product-review-sentiment-analysis](https://github.com/destinyarx/English-Tagalog-Product-Reviews-Sentiment-Analysis.git`
2. Navigate to the project directory: `cd English-Tagalog-Product-Reviews-Sentiment-Analysis`
3. Create a virtual environment: `python -m venv venv`
4. Activate the virtual environment:
   - On Windows: `venv\Scripts\activate`
   - On macOS and Linux: `source venv/bin/activate`
5. Install the required packages: `pip install -r requirements.txt`
6. Run the development server: `python manage.py runserver`

## Usage

1. Access the web app in your browser at `http://localhost:8000`.
2. Input a product review in Tagalog or English.
3. Click the "Analyze" button to obtain the sentiment analysis results.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the creators of Django, TensorFlow, and Selenium for their amazing tools and libraries.

Feel free to contribute or report issues to help improve this project!
