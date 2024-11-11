# JavaScript-MiniProject

![image](https://github.com/user-attachments/assets/5fa8bb1a-0923-4159-997b-9f3250978f21)

## About The Project

This is a Hello World in Javascript using express and uploaded on any cloud provider.

## Table of Contents

<ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#overview">Overview</a></li>
        <li><a href="#features">Features</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#running-the-project">Running the service</a></li>
        <li><a href="#running-with-docker">Running with docker</a></li>
      </ul>
    </li>
    <li>
      <a href="#contributing">Contributing</a>
    </li>
 </ol>

## Overview

This Hello world opens doors to possibilities that can be done in programming with javascript because it is the first line of code that is learned in any language.

## Features

<div>
  <ul>
      <li> <b>Lightweight:</b> Based on a minimal Node.js setup.</li>
      <li> <b>Simple HTTP Server:</b> Responds with "Hello World" on the root route.</li>
      <li> <b>Fast Startup:</b> Quick to build and run.</li>
  </ul>
</div>

## Built With

[![Node.js][nodejs.com]][nodejs-url]
[![Docker][docker.com]][docker-url]

<!-- GETTING STARTED -->
## Getting Started

## Prerequisites

Before you begin, make sure you have the following tools installed on your machine:

- **Node.js 18.20.4 or higher** - [Download Node](https://nodejs.org/en/download/package-manager)

If you don't have any of these tools installed, follow the provided links to install them.


## Installation

1.- Clone the repository
   ```sh
   git clone https://github.com/Retrofiyer/JavaScript-MiniProject.git
   cd JavaScript-MiniProject
   ```
2.- Build project using node.js
 ```sh
   npm install
   ```
## Running the project

  ```sh
    npm start
   ```

Open any browser and type

 ```sh
   localhost:8080
   ```

## Running with docker

1.- Making Docker Pull or Build docker image

 ```sh
   docker pull retroandre/hello-javascript:latest
   ```
```sh
   docker build -t <any-name> .
   ```
2.- Last make a docker run

 ```sh
   docker run -p 8080:8080 retroandre/hello-javascript:latest # or any-name
   ```
3.- Open any browser and type

 ```sh
   localhost:8080
   ```

## Contributing

I would like you to contribute to this project. Whether it's fixing a bug, adding a new feature or improving the documentation, your help is always welcome. Please email me at `sebitas5225@gmail.com` with all the details for improvement.

<!-- LINKS & IMAGES -->

[docker.com]: https://img.shields.io/badge/Docker-black?style=for-the-badge&logo=docker&logoColor=white
[docker-url]: https://www.docker.com/
[nodejs.com]: https://img.shields.io/badge/Node.js-black?style=for-the-badge&logo=node.js&logoColor=white
[nodejs-url]: https://nodejs.org/
