# YouTube Video Sentiment Analysis

The YouTube Video Sentiment Analysis project is a Python-based application that utilizes the YouTube API to retrieve comments from a specific video, preprocesses those comments, and determines their sentiment as positive or negative using TextBlob and NLTK libraries. Additionally, the GoogleTrans library is used for translation if needed.

## Features
- Fetch comments from a specified YouTube video using the YouTube API.
- Preprocess comments by removing special characters, URLs, and performing other text cleaning tasks.
- Classify comments as positive or negative based on sentiment analysis using TextBlob and NLTK.
- Option to translate non-English comments to English using GoogleTrans before sentiment analysis.

## Technologies Used
- Python
- TextBlob
- NLTK
- GoogleTrans
- YouTube API

## Prerequisites
- Python: Make sure you have Python 3.x installed. You can download it from [python.org](https://www.python.org/).

## Installation
1. Clone the repository:
git clone https://github.com/your-username/youtube-sentiment-analysis.git

2. Navigate to the project directory:
cd 

3. Install the required packages:
pip install -r requirements.txt

## Usage
1. **Obtain YouTube API Key:** Follow the instructions on the [Google Developers Console](https://console.developers.google.com/) to create a project and obtain a YouTube Data API v3 key.

2. **Configuration:** Copy the `config.sample.json` file to `config.json` and add your YouTube API key.

3. **Run the Application:** Execute the Python script with the video URL or ID as an argument.

## Output
The application will output the sentiment analysis results, showing the number of positive and negative comments, along with the overall sentiment score.

## Contribution
Contributions are welcome! Feel free to submit pull requests for improvements or bug fixes. Please ensure that your code adheres to good coding practices and includes appropriate comments.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For questions or suggestions, feel free to contact the project maintainers:
- Royal Garg: [Your GitHub Profile](https://github.com/Rgarg2002)
