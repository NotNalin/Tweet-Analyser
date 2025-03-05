# Tweet-Analyser

## Overview
Tweet-Analyser is a tool designed to analyze tweets for various metrics and insights. It can be used to gather data on tweet sentiment, frequency, and other relevant statistics.

## Features
- Sentiment analysis of tweets
- Frequency analysis of tweet keywords
- Visualization of tweet data
- Configurable settings via `config.json`

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/NotNalin/Tweet-Analyser.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Tweet-Analyser
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
1. Create a copy of config.json.example and name it as config.json:
    ```sh
    cp config.json.example config.json
    ```
2. Fill config.json with your keys from the X developer portal [here](https://developer.x.com/en):
    ```json
    {
        "consumerKey": "",
        "consumerSecret": "",
        "accessToken": "",
        "accessTokenSecret": "",
        "bearerToken": ""
    }
    ```

## Jupyter Notebook
1. Open the notebook file TweetAnalyser.ipynb
2. Follow the instructions in the notebook to perform the analysis.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.