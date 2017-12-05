# FPGA-based Machine Learning Acceleration

We are between 3 and 4 stages of [IoT technology roadmap](https://en.wikipedia.org/wiki/Internet_of_things#/media/File:Internet_of_Things.svg). Current stage is miniaturization  - building energy efficient electronics and software agents and advanced sensor fusion, allowing multiple interconnected objects to behave as single machine. Computing is shifting to the edge of the IoT network mainly because of data gravity (pace of bandwidth growth lags behind pace of data creation). Other factors are privacy (nobody wants to send over insecure network), latency, reliability (make life vs death decisions in-destination, in autonomous cars). To make small IoT agents smarter, they need to do more computing, and energy efficiency is  crucial success factor. 

Besides energy efficiency, there is devices smartness. We electrified things, then digitized things, and now cognify things. Speech recognition, real-time translation, object identification, emotion recognition is now available on smartphones and evem smaller devices. The majority of these algorithms today are driven by Deep Learning, machine learning inspired by neuroscience, made possible due to computation capacities and big data. Move of these algorithms from data centers to small intelligent “things” is not straightforward. In some cases small reduce of accuracy is possible with huge saving in performance, with use of smaller networks, sparse, ternary or binary networks and integer (or sub-integer) data types instead of floats.

Burning software bits into silicon hardware is the way to achieve energy and space efficiency. We believe that FPGA is the “next big thing” in AI hardware and custom FPGA and ASIC chips will transform data centers from one side, and small “thins” or devices from other. Data center performance per watt and performance per dollar matters. Ultimate flexibility of FPGA chips allows dynamic reconfiguration (optimization) of hardware for specific task. 

Artificial Intelligence (AI) is growing. AI is becoming new programing paradigm. We [computer scientists and software engineers] approach AI in form of Machine Learning (ML) and particularly Deep Learning. Modern machine learning achievements are possible due to data and computing power, which were not available 10 years ago. The need of computing is growing faster than computing capacity of general purpose hw (processors and coprocessors). With growing complexity of ML algorithms, and data amounts, hardware acceleration is still important. 



## Hardware Accelerators
While GPU acceleration (lead by NVidia) is de-facto standard in today’s mainstream deep learning, other acceleration technologies emerge.
![Titan X](http://images.nvidia.com/pascal/img/titanx/titanx-design.png "Titan X")
Titan X, Most popular GPU used for Deep Learning today. Source: nvidia.com
