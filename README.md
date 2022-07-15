# docker-simcity

Docker image of simcity running on js-dos

run the following to build
`docker build -t docker-simcity --build-arg GAME_URL=https://github.com/magicalyak/docker-simcity/raw/main/simcity.zip --build-arg GAME_ARGS=\"SIMCITY.EXE\" .`

once you have built the image, run with 

`docker run -d -p 8000:8000 docker-simcity`
