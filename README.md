# Interactive Sentiment Analysis Application

This project analyzes YouTube comments to determine their sentiment using various machine learning techniques.

## Features

- Fetch YouTube comments using the YouTube API
- Perform sentiment analysis using VADER Sentiment and TextBlob
- Display sentiment results in a user-friendly interface
- Export sentiment analysis results to CSV

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/Interactive-Sentiment-Analysis-Application.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Interactive-Sentiment-Analysis-Application
    ```

3. Create a virtual environment:

    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On Windows:

        ```bash
        venv\Scripts\activate
        ```

    - On macOS and Linux:

        ```bash
        source venv/bin/activate
        ```

5. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Flask application:

    ```bash
    python App.py
    ```

2. Open your web browser and navigate to `http://localhost:5000`.

3. Use the interface to upload CSV files and analyze YouTube comments.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
