## ISN: Large-capacity Image Steganography Based on Invertible Neural Networks (CVPR2021)

### If you want to communicate with me about the ISN, please concact me without hesitating. My email:  
 nkwangrong@mail.nankai.edu.cn 

 ### test example
 #### 1 hidden image
 the container image and the host image 

![1_cont](./doc/1_cont.png) ![1_host](./doc/1_host.png)

 the hidden image and the revealed  hidden image 

![1_serc](./doc/1_secr.png) ![1_host](./doc/1_secr_rev.png)

 ####  5 hidden images
 the container image and the host image 

![5_cont](./doc/5_cont.JPEG) ![5_host](./doc/5_host.JPEG)

 the 5 hidden images  

![5_serc](./doc/5_secr.JPEG) 

the 5 revealed  hidden images 

![5_host](./doc/5_secr_rev.JPEG)

 #### You can find the results of hiding 2 ~ 3 images  in the 'doc' folder.
 
### Average PSNRs of the revealed hidden images and the container images for embedding 1∼5 images.

 ![hidden_15](./doc/hiding_15png.png)

### Comparison with DeepSteg[5] 
#### [5] Shumeet Baluja. Hiding images within images. IEEE TPAMI, 2020.

Objective comparison using PSNR/SSIM. - h1 and - h2 means to hide 1 and 2 images respectively. (c) means cross-
domain testing, i.e. the model trained on another dataset is tested
directly without fine-tuning.

 ![comp](./doc/comp_psnr.png)
 
Visual comparisons for hiding and revealing two images.

 ![vis_2hidden](./doc/vis_2hidden.png)

 ### Jittor 
Compared with pytorch, using Jittor can accelerate the inference speed  and reduce the memory at the same time at different resolutions. 

 ![jittor](./doc/jittor.png)

 ### Citation

If you find our work useful in your research, please consider citing:

@inproceedings{shaopingluISN2020,

  title={Large-capacity Image Steganography Based on Invertible Neural Networks},

  author={Shao-Ping Lu,  Rong Wang,  Tao Zhong,  Paul L. Rosin },

  booktitle={CVPR},

  year={2021}
  
}
