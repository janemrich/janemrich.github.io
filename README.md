# Data Scientist

#### Technical Skills: Python, SQL, PyTorch, (3D) Computer Vision

## Education
M.S., Autonomous Systems \
@ Technische Universität Darmstadt (_September 2022_)

Exchange Year\
@ University of Technology Eindhoven (_September 2019_)

B.S., Computer Science\
@ Technische Universität Darmstadt (_September 2018_)

Allg. Fachhochschulreife (A-Levels)\
@ Abendschule Berufsschule Plus (_July 2015_)

## Work Experience
**Research Assistant Intern @ Fraunhofer IGD (_October 2022 - May 2023_)**
- study of **deep learning 6D Object Pose Estimation**
- supporting my master thesis
- continued research after thesis

**Data Scientist Intern @ Bosch Rexroth (_July 2019 - October 2020_)**
- Spearheaded deep **anomaly attribution for predictive maintenance**
- Designed and developed a prototype using **Keras** and Deeplift,
which excelled at identifying sensor signals correlated with machine failure in real-world data
- Researched effort to switch database from Hadoop to timeseries database **InfluxDB**

**Tutor @ TU Darmstadt (_April 2018 - July 2018_)**
- Conducted tutoring sessions in Distributed Systems

**Student Assistent @ TU Darmstadt (_August 2016 - June 2018_)**
- Engaged in programming projects in **Java** to support research in train systems

**Repair Engineer @ Bosch Rexroth (_February 2015 - September 2015_)**
- “Played a crucial role in the Quality Assurance team”, ensuring the reliability of high-precision electric motors.
- Repair of synchronous servomotors

**Apprentice Mechatronics @ Bosch Rexroth (_September 2011 - February 2015_)**
- Gained real-world experience in robotics and automation in manufacturing with **PLC**, **electronics**, **mechanics** and **hydraulics**

## Projects

### Deep Stereo RGB-only Dense 6D Object Pose Estimation (Master Thesis)
![Pose Estimation](/assets/img/render_bboxes.jpg)

![Paper](https://github.com/janemrich/denstereo2/blob/denstereo/thesis.pdf) | [Repository](https://github.com/janemrich/denstereo2)
- Leveraging stereo, we extend the state-of-the-art in the task of direct 6D pose regression.
- Created new real-world and synthetic data with blender simulation and Kinect cameras
- Preprocessed and cleaned data for use in a common format
- Implemented a end-to-end deep learning model with **PyTorch** on a GPU Cluster with **Slurm** and **Docker**

### Deep Reinforcement Learning Agents For Pommerman
![Pommerman](/assets/img/pommerman.gif)
- Top three agent in student competition
- Deep neural network architecture design
- **Reinforcement learning** algorithm and environment design

### Deep Unsupervised Denoising For Interleaved X-Ray Channels
![X-ray](/assets/img/x_ray.webp)
[Paper](/assets/pdf/Demosaicing_and_Denoising_For_Interleaved_X_Ray_Channels.pdf) | [Repository](https://github.com/janemrich/cvlab)
- Trained deep neural nets for denoising in **PyTorch**
- Unsupervised, no ground truth data available
- Adaption of SOTA methods to the specific statistics of X-Ray images required understanding of the physics of the system
- Loss function had to fit the statistics of the noise generation process

### Multi-Object Tracking
- Tracked 3D poses of objects in **C++**
- Filtering with a particle filter over the probability distribution

### Genetic Algorithm for Build Order Optimization in StarCraft II (Bachelor Thesis)
[Repository](https://github.com/janemrich/BOoptimizer)
- wrote a genetic algorithm in **Java** to optimize game-playing
- parallel evaluation of build orders with a **C++** game bot

### Solar plus Battery EV charging park energy and cash flow simulator
[Repository](https://github.com/janemrich/ev-solar-park)
- Simulates a solar EV charging park in python with probability distributions
- Reports cash flows and balance sheet

### Electric Vehicle Comparison Website
[Repository](https://github.com/janemrich/eautoinfo.com) | [Website](https://eautoinfo.com/)
- wrote a EV Comparison Website in **React**
- self-hosted with **Docker** and **Virtual Root Server**