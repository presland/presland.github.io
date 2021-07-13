---
layout: post
title:  "What is Edge Intelligence"
date:   2021-07-13 16:41:14 +0100
categories: jekyll update
---

This is the first post in a blog dedicated to exploring the nascent synthesis of Artificial Intelligence (AI) and Edge Computing into Edge Intelligence. The post aims to introduce the driving forces in this synthesis and review benefits compared to cloud based solutions. That being done we can enjoy a more detailed technological exploration in future posts.

__Edge Intelligence is the combination of Edge Computing and Artificial Intelligence__.

Edge intelligence is a synthesis of multiple technolgies that bring processing of AI algorithms to the computing network's edge, local to the device generating the data, and away from centralized servers. The exact definition of the _edge_ depends on the use case - but it could be a smartwatch, mobile phone, IoT device, robot or cell tower. Often location intelligence is also required to interpret results.

__What is Edge Computing?__

Although not a new concept the Edge has had a breakthrough in recent years thanks to the rapid development of technologies such as mobile devices, machine learning and LoRaWAN networks. To be considered _on-the-edge_ the computing power and data storage must be at the same location as the data is collected. Examples of a things that may at first seem like edge intelligent but are _not_ an actual edge solution are virtual assistance like Alexa, Siri or Google's assistant. In these examples human speach data is sent to a cloud backend for processing before the result is returned.

__What is Artificial Intelligence?__

Although no agreed clear definition exists Artificial Intelligence for our purpose can been seen as a machine approximating human reasoning. It does this in general by combining machine learning with automation. Good examples from Computer Vision are object detection or semantic segmentation that might be applied to autonomous vehicles. 

__What are the benefits of Edge Intellignece?__

Most readers of this post require no other justifiation for Edge Intelligence other than just _'because we can'_. But a case has to be made for how it can generate a better business compared to cloud-based solutions. So here are some of the benefits:

1. __Latency__: Round-trip data transfer response times for a cloud backend are typically of the order of 100 milliseconds. For many applications this is not a problem but sometimes latency is (safety) critical (e.g. autonomous cars).

2. __Real-time__: Analytics performed one the edge can approach real-time performance if carefully implemented. This is an important consideration in time critical applications. For example a time discrepency in motion control for pick-and-place robots on a production line can lead to a defective product being shipped or cause infrastructure damage.

3. __Scalability__: As data volumes grow in centralized cloud based solutions data transfer becomes a bottleneck. Edge-based solutions do most processing locally and therefore suffer less from volume problematics. As an example consider the relative scalability of analysing video streams from thousands of devices in the cloud or individualy on each device. 

4. __Privacy__: Sending data to the cloud creates a vuneralability to online attack. Edge solutions often process on device or operate in a closed network. The risk of attack is therefore minimized.

5. __Automation__: Edge Intelligence is a great automation enabler. Consider process control in pharmaceutical production. Hundreds of sensors constantly monitor the process state and equipment diagnostics. AI can use that data to iteratively optimize processes "on-the-fly". 

6. __Cost__: We have seen how Edge Intelligence can reduce latency in decision making and improve scalability both of which reduce costs. It also increases energy efficiency by greatly reducing data transfer bandwidth and minimizes the need for costly cloud computing. This must however be offset by the cost of supplying hardware with sufficient local computing power.

__Realizing the potential of the IoT.__

The internet of things (IoT) hass made computing ubiquitous. Individuals own and interact with an increasing number of IoT enabled smart devices (phone, watch, wearable) and find themselves in an IoT enabled environments (SmartCity, SmartMobility). Each of these was probably created in a process that involved some degree of automation connected by IoT.

Edge Intelligence realizes the potential of the ubiquitous IoT by allowing each IoT end-point make independent decisions that bring value to both the user and service provider. It can do this without having to send sensitive private information to a central location. 

But do not think that the Edge will replace the cloud. They are complementary. Data will continue to be processed in the cloud but users private data will increasingly be processed on the Edge.