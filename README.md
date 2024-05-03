# the-ai-briefing-room


![image](https://github.com/jiajingchen1995/gemini-hackathon/assets/45247795/d1cfc4fc-2e6c-48fa-8376-a6469aca70b4)

### Installation

First, ensure you have Python installed on your system. Then, install the required dependencies:

`pip install -r requirements.txt`

### Running the Script
To generate a podcast episode, use the following command:

`python main.py [episode number]`

Replace [episode number] with the actual number of the episode you want to generate.

### Output
After running the script, the output will be organized into folders by date within the output folder. Each folder will contain three .mp3 files for the podcast in different languages (Chinese, English, Spanish) and a .txt file containing the podcast title, description, and script. See the example structure below:
```
/output
  /2024-04-23
    Chinese_final_podcast.mp3
    English_final_podcast.mp3
    Spanish_final_podcast.mp3
    podcast_data.txt
```


### Configuration
Create a .env file in the root directory of your project and add the following content:

```
GOOGLE_GEMINI_API_KEY = [your Gemini key]
EMAIL = [anchor login email]
PASSWORD = [anchor login password]
```

Replace [anchor login email] and [anchor login password] with your actual login credentials for Anchor.
