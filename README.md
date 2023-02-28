# Zhonglin Project2 Microservice Rust

## Key Objectives of Project
In project 2, the main purpose is to build a functional Web Microservice using Rust based on Kubernetes and deploy and host it on AWS.
I create a simple actix Microservice for top 10 US universities recommendation

This actix Microservice has multiple routes:

A. type: "/" that returns a message : "Hello, random best movies around the world!"

B. type: "/movie" that returns a random best movie in the list of the world top 10 best movies

C. type: "/version" that returns the version of the service 
