
### How to use:
Download any number of images from Google image search.

- run as 

`python image_download.py <query> <number of images>`

where:

`<query>` is the the query to search for.

`<number of images>` min(`<number of images>`, total google results) will be downloaded.

All the images are downloaded from Google image search. These should be used for educational purposes only. Copyright is owned by the respective websites.

### Requirements:
1. You will need to `pip install selenium` and follow the procedures [here](https://pypi.python.org/pypi/selenium) to install the correct drivers for whatever browser you want to use (the code uses Firefox by default)

### Notes:
2017-11-07
1. Requires Pyton 3.6 to run
2. Updated to use the requests package (instead of urllib)

### Helpful Resources:
1. https://stackoverflow.com/questions/34692009/download-image-from-url-using-python-urllib-but-receiving-http-error-403-forbid
