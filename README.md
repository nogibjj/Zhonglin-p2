# Zhonglin Project2 Microservice Rust

## Key Objectives of Project
In project 2, the main purpose is to build a functional Web Microservice using Rust based on Kubernetes and deploy and host it on AWS.
I create a simple actix Microservice for top 10 US universities recommendation

This actix Microservice has multiple routes:

A. type: `/` that returns a message : "This is a random best university of the US generator!"

B. type: `/university` that returns a random university in the list of the US top 10 best universities

C. type: `/version` that returns the version of the package 

## 1. `cargo run`
<img width="675" alt="image" src="https://user-images.githubusercontent.com/112585430/221992977-b85337d9-3a34-42ab-b561-2bb50bbe581f.png">
Initiating message:  

<img width="683" alt="image" src="https://user-images.githubusercontent.com/112585430/221993156-9243a1c6-fc8f-49f4-affc-ff5439f5a48c.png">
<img width="715" alt="image" src="https://user-images.githubusercontent.com/112585430/221993315-e8633cc8-0f87-45af-90f3-a34b2c253b9b.png">
<img width="715" alt="image" src="https://user-images.githubusercontent.com/112585430/221994784-b69fc902-6ec2-4ce2-8220-c7b3228325cc.png">

## 2. build container