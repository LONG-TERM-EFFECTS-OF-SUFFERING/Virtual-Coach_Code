# Virtual-Coach_Code

In order to clone and execute this repository, follow the next steps:
1. Clone it where you need it.
2. After you have clone it, insert the next command insite the repository in order to pull the code from Backend and Frontend:
    ```
    git submodule update --init --recursive
    ```
3. Finally, build the Docker containers and start them:
    ```
    docker compose up --build
    ```
    - The backend will be running at `localhost:8000`
    - The frontend will be running at `localhost:80`

## Some other notes
- **Submodules documentation:** [Documentation from Git](https://git-scm.com/book/en/v2/Git-Tools-Submodules) and [Documentation from Github](https://github.blog/2016-02-01-working-with-submodules/)
- **Tutorial from where I took the containers:** [YouTube Video](https://www.youtube.com/watch?v=oX5ElI-koww)
- **About Docker**
    - **`docker compose build`:** It builds the images in the *docker-compose.yml*
    - **`docker compose up`:** It starts the containers.
    - **I have a lot of containers:** [This is how you can delete it all](https://docs.tibco.com/pub/mash-local/4.3.0/doc/html/docker/GUID-BD850566-5B79-4915-987E-430FC38DAAE4.html)

