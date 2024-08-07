---
layout: post
title:  "Week 7"
date:   2024-07-25 11:00:13 +0530
categories: jekyll update
toc : true
---

In the previous week, I successfully completed modifying and testing the GUI, ensuring that it works as intended. My goal this week was to tackle the issue I was facing while subscribing to the webcam node.

To ensure there were no issues with the RADI container, I placed my webcam test scripts within the container. By accessing the container through the entrypoint `/bin/bash`, I checked their functionality using two separate terminals. Since bash doesn't support a GUI interface, I printed the pixel values of the input webcam feed as shown below:

With this test, I confirmed that the container had no issues. In the follow line exercise, we had been using a separate `camera.py` script that subscribes to the webcam node and obtains the feed. I decided to omit it altogether and include the entire functionality within the `HAL.py` file. Below is the updated version of the `HAL.py` file:

When running the exercise, I obtained the webcam feed perfectly, as seen in the video below:

<iframe width="560" height="315" src="https://www.youtube.com/embed/vQvqVLenFzo?si=s5kPmxkWWu8IAzaD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

