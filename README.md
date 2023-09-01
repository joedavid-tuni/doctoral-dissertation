# Source code for PhD Dissertation

This meta repository contains supplementary material for Joe David's Doctoral Dissertation "A Design Science Research Approach to Architecting and Developing Information Systems for Collaborative Manufacturing: A Case for Human-Robot Collaboration".

![Five git repositories that contains source code for the artefacts developed in the dissertation](/assets/apx_git.png)

## Interaction UI
> This repository contains the source code for the mixed-realit application as a React project. The code is purely front-end code in JavaScript and CSS. The repository can be found [here](https://permanent.link/to/jd-doctoral-dissertation/interaction-ui).

## Web Server
> This repository contains the source code (JAVA) for the web server that forms the backend of the foregoing interaction UI and also is resonsbile for instantiating and the human and robot agents in JADE. The repository can be found [here](https://permanent.link/to/jd-doctoral-dissertation/web-server).

## NXAgent
> This repository contains the source code for JADE agent that represents the KBE software, SiemensNX. It is responsible for looking up the RMS server and instantiating a JADE agent so that the other agents can communicate with Siemens NX. The repository can be found [here](https://permanent.link/to/jd-doctoral-dissertation/nxagent).

## Interaction Model

> This repository contains source code for interfacing MediaPipe with the application. It is responsible for detecting the operator hands and transforming that into mouse coordinates for the interaction UI. The repository can be found [here](https://permanent.link/to/jd-doctoral-dissertation/interaction-model).

## Robot Module

> This module allows communication with the UR5 robot used in the research setting. The repository can be found [here](https://permanent.link/to/jd-doctoral-dissertation/robot-module).

## License

License information can be found in the individual repositories.