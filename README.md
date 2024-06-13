# Seismic Denoising and Resolution Enhancement Using GANs
![Alt text](Images/sr_gan_pari_inl_461_v3.png)
## Overview
This repository contains the code and link to datasets for the paper **"Seismic Denoising and Resolution Enhancement Utilizing Generative Adversarial Network (GAN) Families: An Application on Taranaki Basin Dataset"** by João Rafael B. Da Silveira and José J. S. de Figueiredo. The study focuses on enhancing the quality of seismic data by using GANs to improve resolution and reduce noise.

## Instructions

1. **Clone the Repository**
   ```bash
   git clone [https://github.com/LpsUfpa/Seismic-Denoise].git
   cd yourrepository
2. **Install Dependencies**
Make sure you have Python installed. You can install the required packages using pip:
   ```bash
   pip install -r requirements.txt
3. **Download Dataset**
The seismic data used in this study is from the Parihaka and Kerry fields in New Zealand’s Taranaki Basin. They can be obtained for free on the website.

[Open_data#New_Zealand_3D](https://wiki.seg.org/wiki/Open_data#New_Zealand_3D).

# Note on Images
Images provided in this repository are examples and may not be present in the original article. They are included to help understand the implementation and results of the GAN-based approach for seismic data enhancement.

# Abstract
Seismic data often suffers from noise and low resolution, posing challenges for accurate interpretation and analysis. This study addresses these issues by exploring the application of GAN families to enhance the quality of seismic data. The proposed approach involves utilizing GANs, comprising a generator and a discriminator network. The generator is trained to generate refined seismic images with reduced noise and enhanced resolution, while the discriminator evaluates the authenticity of these images against actual seismic data. Through iterative training, the generator improves its ability to produce high-quality seismic images. Evaluation metrics, such as Mean Squared Error (MSE) between the frequency spectra of actual and predicted signals, demonstrate significant improvements in denoising and resolution capabilities. The effectiveness of the proposed method is validated using both synthetic and real datasets, incorporating non-linear noise. This research contributes to advancing the quality and reliability of seismic data interpretation and analysis.

# Citation
If you use this code or dataset in your research, please cite the paper:
   ```bash
   @article{silveira2024seismic,
     title={Seismic Denoising and Resolution Enhancement Utilizing Generative Adversarial Network (GAN) Families: An Application on Taranaki Basin Dataset},
     author={Silveira, João Rafael B. Da and Figueiredo, José J. S. de},
     journal={IEEE Transactions on Geoscience and Remote Sensing},
     year={2024},
     volume={XX},
     number={X},
     pages={1-10}
   }
