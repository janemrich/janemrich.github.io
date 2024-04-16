## Projects

### Chess Document AI | [pawnparse.com](pawnparse.com)
![Schach](/assets/img/Fischer_Score_Card.jpg)


Developing Optical Character Recognition for chess tournaments.
- Fine-tuning Vision and LLM Transformers for handwritten chess notation
- Developing text recognition for chess notation
- Data collection, Processing, Labeling and Design

### Deep Stereo RGB-only Dense 6D Object Pose Estimation (Master Thesis) [Paper](https://github.com/janemrich/denstereo2/blob/denstereo/thesis.pdf) | [Repository](https://github.com/janemrich/denstereo2)

![Pose Estimation](/assets/img/render_bboxes.jpg)


Researched RGB-only 6D object pose estimation.
- Correctly identified which method in the literature will become state-of-the-art with further training and extended the method to a dual camera setup
- Created new real-world data with Kinect cameras, using camera calibration, and 50k synthetic samples with blender rendering and physics simulation on a Slurm cluster and generated 500k+ labels on a Slurm cluster with Python, Blender, Numpy and Numba
- Trained PyTorch model with 8 loss functions on a A100 GPU cluster with up to 8 GPUs per model with Docker containers inside Slurm jobs, optimized Hyperparameters
- Added new modalities to the model by combining it with depth regression models and tested various forms of image fusing neural network architectures for dual cameras

### Deep Reinforcement Learning Agents For Pommerman
![Pommerman](/assets/img/pommerman.gif)
- Top three agent in student competition
- Deep neural network architecture design
- **Reinforcement learning** algorithm and environment design

### Deep Unsupervised Denoising For Interleaved X-Ray Channels
![X-ray](/assets/img/x_ray.webp)
[Paper](/assets/pdf/Demosaicing_and_Denoising_For_Interleaved_X_Ray_Channels.pdf) | [Repository](https://github.com/janemrich/cvlab)

Researched deep unsupervised denoising for novel x-ray sensors.
Successfully trained unsupervised denoiser in PyTorch, which required understanding of the specific statistics of x-ray sensors for correct loss function with Numpy and SciPy
- Trained deep neural nets for denoising in **PyTorch**
- Adaption of SOTA methods to the specific statistics of X-Ray images required understanding of the physics of the system
- Loss function had to fit the statistics of the noise generation process

### Predictive Maintenance Internship
Worked on improving a deep predictive maintenance product.

- Promoted deep anomaly attribution for predictive maintenance on my initiative. Designed and developed a prototype using Autoencoders, Keras and Deeplift, which succeeded at identifying timing and sensor signals correlated with machine failure in real-world industrial IoT data, saving daily work for the 10-person customer service team
- Researched, tested and presented time series databases, prompting the team to switch to InfluxDB
- Developed data processing tooling with Pandas and Bokeh

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
