1. Install poetry
pip install poetry
2. Create project
poetry init
3. activate environment
poetry shell
4. install packages
poetry add colorama
5. look at installed packages
poetry show
6. deactivate environment
deactivate


1. build image
docker build . -t assistant
2. run docker container
docker run --name clibot -it assistant