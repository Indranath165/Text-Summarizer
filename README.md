<h1>Text-Summarizer</h1>
This repository contains a Python Flask web application that leverages the power of Natural Language Processing (NLP) techniques to generate concise summaries of text passages. By employing advanced algorithms and linguistic analysis, the application intelligently condenses the provided text while ensuring the main ideas and crucial information are preserved.
<br>
Furthermore, the application offers a user-friendly interface that presents the original passage alongside the generated summary, accompanied by their respective word counts. This allows users to easily compare the lengths and assess the level of information compression achieved by the summarization process.
<br>
With the live deployment of the application, users can seamlessly access the text summarization functionality from anywhere. By visiting the provided link, they can input their desired text passage, trigger the summarization process, and receive the condensed summary promptly. This practical and efficient solution simplifies the task of extracting essential insights from lengthy texts, saving users valuable time and effort.
<br> <br>
<b>Check out the live deployed version of the project: </b> <a href="https://indranath165-text-summarizer.onrender.com/" target="_blank">Text Summarizer</a>.
<h2>Installation</h2>
To run the Text Summarizer application locally, follow these steps:
<ol>
    <li>Clone or download this repository to your local machine.</li>
    <li>Navigate to the project directory: <code>cd Text-Summarizer</code></li>
    <li>Create and activate a virtual environment (optional but recommended): <br> <code>python3 -m venv venv <br> 
 source venv/bin/activate</code></li>
    <li>Install the required dependencies: <code>pip install -r requirements.txt</code></li>
    <li>Start the Flask development server: <code>python app.py</code></li>
    <li>Open your web browser and access the application at <a href="http://localhost:5000" target="_blank">http://localhost:5000</a>.</li>
</ol>
<h2>Features</h2>
<ul>
    <li>Automatically generates summaries of text passages.</li>
    <li>Provides word count for the original passage and the generated summary.</li>
    <li>User-friendly web interface built with HTML and CSS.</li>
    <li>Powered by Python Flask and NLP libraries.</li>
</ul>
<h2>Usage</h2>
<ol>
    <li>Access the live deployment of the application at <a href="https://indranath165-text-summarizer.onrender.com/" target="_blank">Text Summarizer</a>.</li>
    <li>On the web interface, you will see a text input field.</li>
    <li>Paste or type the desired text passage into the input field.</li>
    <li>Click on the "Submit" button.</li>
    <li>The application will process the input and generate a summary.</li>
    <li>The original passage and the generated summary, along with their respective word counts, will be displayed side by side.</li>
</ol>
<h2>How It Works</h2>
The text summarizer application uses Natural Language Processing techniques to generate a concise summary of a given text passage. The NLP libraries, such as NLTK and spaCy, are leveraged for tokenization, sentence segmentation, and feature extraction. <br> <br>
The application follows these steps to generate the summary:
<ol>
    <li>Receive the input text passage from the user.</li>
    <li>Preprocess the text by removing unnecessary characters and formatting.</li>
    <li>Tokenize the text into words and sentences.</li>
    <li>Calculate the word count of the original passage.</li>
    <li>Apply NLP techniques to extract important features from the text.</li>
    <li>Generate a summary based on the extracted features.</li>
    <li>Calculate the word count of the generated summary.</li>
    <li>Display the original passage, the summary, and their respective word counts on the web interface.</li>
</ol>
<h2>Contributions</h2>
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:
<ul>
    <li>Fork the repository.</li>
    <li>Create a new branch.</li>
    <li>Make your changes and commit them.</li>
    <li>Push your changes to your forked repository.</li>
    <li>Submit a pull request describing the changes you've made.</li>
</ul>
