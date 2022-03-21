This is a Dockerized version of the repo: https://github.com/anfederico/flaskex
This is not my repo, but I had to modify the file requirements.txt to fix a version bug.

Simply run the image and open the port 5000:

docker run --rm -it -p 5000:5000 stygian2a/flaskex

Flaskex should be available on http://localhost:5000/