<h2>Hi 👋, I'm Safkat, an automotive researcher and developer </h2>
<p>
I’m passionate about shaping the future of mobility through research and development in automated driving systems, robotics, and AI. I enjoy building intelligent, real-world solutions that blend engineering with cutting-edge technologies.
</p>

## 🔭 Projects
# 1. Master’s Dissertation
Repository: *(Private Repository)*

Understanding the influence of environmental factors—like road geometry, traffic density, and weather—is essential for developing safe and intelligent automated driving systems. However, existing behavioral datasets often differ in structure and lack this crucial contextual data. This thesis proposes a unified framework to harmonize diverse datasets and systematically enrich them with structured environmental information, enabling more holistic behavior analysis for automated driving.

As an example of the enrichment process, the image below illustrates the annotation of road network objects in the **TUMDOT–MUC** dataset. The blue rectangle represents the observed area, while the orange boundaries indicate the extracted junctions. Road user trajectories within the junction area (marked in green) and outside the junctions (marked in grey) are classified and enriched with corresponding road network object details.

The framework is designed to perform such enrichment automatically and can generalize to any trajectory dataset.

<div align="center">
  <img src="https://github.com/user-attachments/assets/22bcb596-d27b-465a-9d83-4307ed484ca8" width="900"/>
</div>


# 2. Traffic Light Detection
Repository: [Traffic-Light-Detection](https://github.com/ika-rwth-aachen/acdc-research-projects/tree/main/reports/05-Traffic-Light-Detection/2023-09_Amin)

As part of the *Automated and Connected Driving Challenges – Research Project*, this work explores onboard camera-based traffic light detection—a critical capability when V2X (Vehicle-to-Everything) support is unavailable. 

To investigate this, I fine-tuned a YOLOv5 model using the **BSTLD** and **DTLD** datasets for traffic light detection. The experimental setup was modeled after this [paper](https://www.mi.fu-berlin.de/inf/groups/ag-ki/Theses/Completed-theses/Bachelor-theses/2020/Hein/), in which the author trained SSD MobileNet v1 and Faster R-CNN Inception v2.

The results demonstrated that **YOLOv5 outperformed** both SSD MobileNet and Faster R-CNN models in terms of detection performance for this scenario.

Furthermore, the project emphasizes the importance of adapting perception systems to **geographical differences in traffic infrastructure**, as shown through cross-dataset evaluations.

Below are example detection results from each dataset:

<div align="center">
  <img src="https://github.com/user-attachments/assets/86038a5e-05a5-4d3b-92af-4f62fcdf4c29" width="45%" style="margin-right: 10px;"/>
  <img src="https://github.com/user-attachments/assets/4e974924-ec9d-4d59-8361-d11adade1b52" width="45%"/>
</div>

# 3. Generative AI Hackathon – EESTECH Challenge Aachen  
Repository: [Customer Experience Enhancement with Public Data and Generative AI](https://github.com/mechgguy/eestech-hackathon)

As part of the **EESTECH Challenge Aachen**, this project aimed to enhance customer satisfaction using generative AI by analyzing GitHub issues from Infineon’s public repositories.

Due to the high volume of technical queries and inconsistent response styles from contributors, ensuring a consistent and user-friendly experience was a challenge. Our solution involved developing a feedback generation system powered by a large language model, which generated responses to each GitHub issue from **three distinct AI personas**—each reflecting a unique communication style, ranging from **highly technical** to **empathetic**.

These personalized responses were integrated into an **interactive chatbot interface**, helping users receive support that aligns with their needs and preferences.

This innovative approach to AI-driven customer interaction earned our team **second place** in the competition.


<h2>🚀 Languages and Tools I Use</h2>
<p><a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="42" height="42" /></a>
<a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="42" height="42" /></a>
<a target="_blank" href="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" style="display: inline-block;"><img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="42" height="42" /></a>
<a target="_blank" href="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" style="display: inline-block;"><img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="42" height="42" /></a>
<a target="_blank" href="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" style="display: inline-block;"><img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="opencv" width="42" height="42" /></a>
<a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="42" height="42" /></a>
<a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="42" height="42" /></a>
<a target="_blank" href="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" style="display: inline-block;"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" alt="matlab" width="42" height="42" /></a>
<a target="_blank" href="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" style="display: inline-block;"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="42" height="42" /></a>
<a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="42" height="42" /></a>
<a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="42" height="42" /></a>
<a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="42" height="42" /></a>
<a target="_blank" href="https://www.ros.org/" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/ros/ros-original.svg" alt="ros" width="42" height="42" /></a></p>


<h2>⚡️ Where to find me</h2>
<p>
  <!-- LinkedIn -->
  <a target="_blank" href="https://www.linkedin.com/in/khsafkatamin" style="display: inline-block;">
    <img src="https://img.shields.io/badge/LinkedIn-%230a77b6?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>

  <!-- Email -->
  <a target="_blank" href="mailto:safkat.amin@rwth-aachen.de" style="display: inline-block;">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>

  <!-- Discord -->
  <a target="_blank" href="https://discordapp.com/users/847189190601211954" style="display: inline-block;">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
  </a>
  
  <!-- Portfolio -->
  <a target="_blank" href="https://khsafkatamin.github.io" style="display: inline-block;">
    <img src="https://img.shields.io/badge/Portfolio-121212?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" />
  </a>
</p>



