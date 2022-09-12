# Kolibri Docker project

## Usage:
Clone this repository and then `cd` to `docker` folder. Build the image by using command `docker build -t kilibri:v1 .`

Note: You can replace `v1` tag to whatever Kolibri release you are using. e.g. `v0157` for release `v0.15.7`

## Run locally:
docker run -v /your_local_path/some_dir/some_subdir:/root/.kolibri -p 8080:8080 kolibri:v1
