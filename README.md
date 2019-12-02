# Docker composition of Jenkins

## How to set up

Clone repository

    git clone git@github.com:EvilFreelancer/docker-compose-jenkins.git

Switch work directory to root of project

    cd docker-compose-jenkins

Copy composition config from example

    cp docker-compose.yml.dist docker-compose.yml

Run composition

    docker-compose up -d

After that, if you'll open http://localhost in your browser, you'll see
Jenkins installation page.

By the way, mounting the directory does not work on Windows and MacOS X,
so I strongly recommend that you configure everything on Linux, for example on [Ubuntu Linux](https://ubuntu.com/).

Good luck!

## Links

* https://www.youtube.com/watch?v=Wy3pGG1g-Ms - Original video instruction (on Russian language) about this project with additional details
