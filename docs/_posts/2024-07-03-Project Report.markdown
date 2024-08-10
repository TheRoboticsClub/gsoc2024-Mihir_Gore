---
layout: post
title:  "Project Overview and Commits"
date:   2024-08-10 11:00:13 +0530
categories: jekyll update
---

## What was done

I worked on migrating the Deep Learning Exercises present in Robotics Academy , namely Digit Classifier and Human Detection, to the React.js framework in the new superthin template of the RoboticsAcademy. I also implemented onnxruntime tools in the exercises to reduce inference time. Below is a very brief timeline of the work done. For more information and details, please refer to the specific week in the blog post. 

| **Week**      | **Work Completed** |
| ----------- | ----------- |
| **Community Bonding Period**      | Gained hands-on experience with the ONNX framework, studied the React.js framework, and refreshed knowledge of the required tech stack. |
| **Week 1 and 2**   | Tested previous versions of RADIs to identify functioning deep learning exercises. Studied the codebase of these exercises and tested them with trained models. |
| **Week 3**      | Gained a deep understanding of the new super-thin template for exercises and tested relevant React components. |
| **Week 4**   | Developed launch files for Webcam ROS Nodes and successfully tested them as publisher-subscriber entities within the Docker container. |
| **Week 5**      | Debugged the physical visualization component in RoboticsAcademy, which involved making changes to the launcher files of RoboticsApplicationManager and modifications to the `manager.py` file. |
| **Week 6**      | Enhanced the deep learning processing aspects of the exercises by reducing inference time through the implementation of ONNX Runtime tools such as Model Optimization and Graph Quantization. |
| **Week 7**  | Created a minimal working version of deep learning exercises by obtaining webcam output within the new exercise template. This required rewriting the `HAL.py` and `GUI.py` files to subscribe to the webcam node and display the live feed. |
| **Week 8**      | Developed minimal versions of both exercises, where a demo model was included in the exercise folder. The exercise code was integrated with the code editor on the webpage. For the human detection exercise, an additional launch file was created for non-webcam-based inferencing, and successful testing was performed on both exercises. |


## Skills Learnt
* Docker
* Deep Learning using ONNX
* ROS2 Humble
* React
* Learnt basics of threading
* Learnt how to work with large codebase

## Working Demos:
* Digit Classifier:
<iframe width="560" height="315" src="https://www.youtube.com/embed/s-Pg08RcIUE?si=ylFZTSZy1ebkbEnK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

* Human Detection (Webcam Inferencing):
<iframe width="560" height="315" src="https://www.youtube.com/embed/BIZ6GjSCOU4?si=Nd7KaIActDaDPj8I" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

* Human Detection (Video Inferencing): 
<iframe width="560" height="315" src="https://www.youtube.com/embed/wXNP1eNCP7Y?si=fCF3xvXTAiAZWLlV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## To Do
* Include a file upload button for DL model in the exercises

## PRs Opened

* [Human Detection Migration to Superthin template](https://github.com/JdeRobot/RoboticsAcademy/pull/2689)
* [Digit Classifier Migration to Superthin template](https://github.com/JdeRobot/RoboticsAcademy/pull/2690)
* [Update manager to debug physical visualisation](https://github.com/JdeRobot/RoboticsApplicationManager/pull/155)
* [Add Launchers for DL Exercises](https://github.com/JdeRobot/RoboticsInfrastructure/pull/429)

## Extras
*[Update Carla 0.9.13 to 0.9.15](https://github.com/JdeRobot/BehaviorMetrics/pull/670)
*[Add a webcam publisher-subscriber test](https://github.com/TheRoboticsClub/gsoc2024-Mihir_Gore/tree/main/code/webcam_node_test)
