---
layout: post
title:  "Learning to Drive using Waypoints"
date:   2019-12-29 18:00:00 +00:00
image: /images/NeurIPS ML4AD Architecture.jpg
categories: research
advisor: Prof. Jeff Schneider
authors: Tanmay Agarwal∗, Hitesh Arora∗, Tanvir Parhar∗, Shubhankar Deshpande, Jeff Schneider
advisor_link: https://www.cs.cmu.edu/~schneide/
report: https://ml4ad.github.io/files/papers/Learning%20to%20Drive%20using%20Waypoints.pdf
venue: NeurIPS 2019 Workshop on Machine Learning for Autonomous Driving
poster: /pdfs/Neurips 2019 ML4AD Poster.pdf
media: https://www.talkrl.com/episodes/neurips-2019-deep-rl-workshop

---
We designed an architecture for self-driving agent to learn control directly from semantically segmented images and waypoint input to drive in urban settings in the CARLA simulator for autonomous driving. We used a convolutional autoencoder to extract a lower-dimensional embedding of semantically segmented image and used the Proximal Policy Optimization (PPO) algorithm for policy learning, achieving significant performance improvements on the CARLA benchmark. 
