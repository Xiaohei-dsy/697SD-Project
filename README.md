# 697SD-Project

## Motivation
Mixed reality is the spatial alignment between the real world and virtual world. At every given instance mixed reality systems needs to track user and real-world surroundings, to keep the illusion of “reality”. Multi-modal sensor data is used for tracking and spatial mapping of the real- world. However, most of the existing techniques support movement that are generated from the head movement, also known as macro movement. However, Mixed Reality applications such as surgery requires micro-level tracking of the hand movements.


## Design goals
### Develop 3D pose estimation technique for micro-level tracking of hand movements.
Our goal is Develop 3D pose estimation technique for micro-level tracking of hand movements, we need to implement the micro movement tracking algorithm using deep learning techniques.
We will set up our select fusion on unity, and we will use our data set (Holoset, provided by TA) to train our select fusion model. The data in our project are divided into several types like visual, Inertial, depth and ground truth. After collection, we need to do the data conditioning to process collected data (cleaning, synchronization, etc.). We first need to train our model for macro movements tracking, but our key point is to train our model for micro (hand gesture) movements. We will do research on micro movement 6 degree of freedom pose tracking on a based deep learning model and try to implement our goal. We will Compare accuracy of these two levels, test if the same model works on micro movement data or not.  


## Deliverables
<ol>
<li>Implement the micro movement tracking algorithm using deep learning techniques</li>
<li>Use dataset to train and evaluate the proposed technique (dataset will be provided)</li>
<li>Compare accuracy of trained model on both micro (hand gesture) and macro movements (walking, standing)</li>
</ol>

## System blocks

## HW/SW Requirements
Laptop with CUDA-enabled GPU, Python

## Team members responsibilities
**Shaoyu**: Software design  
**Yifan**: Algorithm design    
**Linghao**: Research    
**Yanan**: Writing paper


## Project timeline

## References
<ol>
<li>SelectFusion: A Generic Framework to Selectively Learn Multisensory Fusion (https://arxiv.org/pdf/1912.13077.pdf)</li>
<li>Learning to Fuse: A Deep Learning Approach to Visual-Inertial Camera Pose Estimation (https://ieeexplore.ieee.org/document/7781768)</li>
<li>Robust Pose Estimation for Outdoor Mixed Reality with Sensor Fusion (https://link.springer.com/content/pdf/10.1007/978-3-642-02713-0_30.pdf)</li>
</ol>
