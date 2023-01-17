# YouTube Python3 - Upload Video
This guide provides and explains a Python script that uploads a YouTube video using the YouTube Data API. The code uses the Google APIs Client Library for Python. 

Guide: https://developers.google.com/youtube/v3/guides/uploading_a_video

# Prerequisites

Install the following in your terminal:

```bash
pip install --upgrade google-api-python-client
pip install --upgrade google-auth-oauthlib google-auth-httplib2
pip install oauth2client
```

# Run

```bash
python3 upload_video.py --file="example.mov" --title="Summer vacation in California" --description="Had fun surfing in Santa Cruz" --keywords="surfing,Santa Cruz" --category="22" --privacyStatus="private"
```

# List of YouTube Categories (Numeric)

https://techpostplus.com/youtube-video-categories-list-faqs-and-solutions/
