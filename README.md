# YouTube Data Scraping Using YouTube API
Welcome to the YouTube Data Scraping repository! This repository provides a set of Google Colab notebooks to help you extract various types of data from YouTube using the YouTube Data API from Google. Whether you're interested in gathering channel information, video metrics, or comment data, you'll find useful code samples to get you started.

## Repository Contents

### 1. YouTubeChanel.ipynb
This notebook contains code to retrieve information about a specific YouTube channel. With this notebook, you can:
- Get the channel description
- Find out the date the channel was launched
- Determine the total number of videos on the channel
- Extract the names of all videos from the channel

### 2. GetLike.ipynb
This notebook provides code to fetch various metrics for YouTube videos. It enables you to:

- Retrieve the number of likes for a video
- Get the view count for a video
- Obtain other relevant metrics associated with the video

### 3. GetComments.ipynb
This notebook includes code to extract comments from YouTube videos. Additionally, it allows you to:

- Extract the text of each comment
- Determine the number of replies each comment has received
- Find out the number of likes each comment has garnered

## Getting Started
You'll need to set up access to the YouTube Data AP to use the notebooks in this repository. Follow these steps to get started:

**1. Obtain API Key:**

- Go to the [Google Developers Console](https://console.developers.google.com/).
- Create a new project or select an existing project.
- Enable the YouTube Data API for your project.
- Create credentials (API Key) for accessing the API.

**2. Clone the Repository:**

```bash
git clone https://github.com/nadia-maarfavi/YouTube.Data.Scraper.git
```
**3. Install Required Libraries:**

Ensure you have the necessary Python libraries installed. You can install them using:
```bash
pip install -r requirements.txt
```

**4. Update API Key:**
In each notebook, replace YOUR_API_KEY_HERE with your actual YouTube Data API key.

## Usage
Open the Jupyter notebook you want to run (e.g., YouTubeChanel.ipynb).
Follow the instructions in the notebook to input the necessary parameters (e.g., channel ID, video ID).
Execute the cells to retrieve and display the data.

## Contributing
If you have any suggestions, bug reports, or feature requests, feel free to open an issue or submit a pull request. Contributions are welcome!

## License
This repository is licensed under the MIT License. See the LICENSE file for more information.
___

Happy scraping! If you have any questions or need further assistance, please don't hesitate to contact me.


