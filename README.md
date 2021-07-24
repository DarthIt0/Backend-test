# Backend-test


## Instructions


#### To clone this repository use:
  
  - git clone https://github.com/DarthIt0/Backend-test.git


#### To download a zip file of the project, access this link:
  
  - https://github.com/DarthIt0/Backend-test/archive/refs/heads/main.zip


#### To build the container, with Docker and docker-compose already installed, run:

  - docker-compose up --build


#### To see if the container image is running, open another terminal tab in the project's folder, and:

  - docker ps


#### To run the ./fetch function inside the container image:

  - docker exec -it container-test python ./fetch https://autify.com https://angel.co https://zoom.com


#### To run the ./fetch --metadata function:

  - docker exec -it container-test python ./fetch --metadata https://www.google.com


#### To see the recorded html files in the container:

  - docker exec -it container-test ls
