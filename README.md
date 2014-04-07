```
usage: pb_shovel.py [-h] [-r] [-o OUTPUT_DIRECTORY]
                    (-f FILE | -u [URLS [URLS ...]])
                    [--images-only | --videos-only] [-n USERNAME]
                    [-p PASSWORD]

optional arguments:
  -h, --help            show this help message and exit
  -r, --recursive       Recursively extracts images and videos from all passed
                        sources.
  -o OUTPUT_DIRECTORY, --output-directory OUTPUT_DIRECTORY
                        The directory the extracted images getting saved in.
  -f FILE, --file FILE  A file containing one or more Photobucket links which
                        you want to download.
  -u [URLS [URLS ...]], --urls [URLS [URLS ...]]
                        One or more links which point to an album or image
                        which is hosted on Photobucket.
  --images-only         Do not download any other filetype besides image.
  --videos-only         Do not download any other filetype besides video.

Authentication:
  -n USERNAME, --username USERNAME
                        The username or email which is used to authenticate
                        with Photobucket.
  -p PASSWORD, --password PASSWORD
                        The matching password for your account.
```
