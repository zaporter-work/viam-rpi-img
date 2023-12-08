To build:
follow docs https://github.com/OctoPrint/CustoPiZer

Put input.img in $PWD
This (below) will create output.img:
docker run --rm --privileged -v "$PWD":/CustoPiZer/workspace -v "$PWD/config_64.local":/CustoPiZer/config.local ghcr.io/octoprint/custopizer:latest
