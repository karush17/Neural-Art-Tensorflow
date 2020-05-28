# Neural-Art-Tensorflow
An implementation of the paper [A Neural Algorithm of Artistic Style](https://arxiv.org/pdf/1508.06576v2.pdf)

<p align="center"><img src="output/1.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/2.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/3.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/4.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/5.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/6.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/7.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/8.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/9.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/10.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/11.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/12.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/13.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/15.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/16.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/17.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/18.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/19.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/20.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/21.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/22.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/23.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/24.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/25.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/26.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/27.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/28.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/29.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/30.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/31.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/32.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/33.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/34.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/35.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/36.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/37.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/38.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/39.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/40.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/41.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/42.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/43.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="output/44.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="output/45.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;</p>  
  
  # Implementation
  
  Download the repository and run the following- 
  ```
  pip install -r requirements.txt
  python neural_style.py --content <path to content image> --styles <path to style images> --output <result destination>
  ```
  
  # Requirements  
  
  __Data Files__  
  
  Pre-Trained VGG Network (VGG19) weights can downloaded from [here](http://www.vlfeat.org/matconvnet/models/imagenet-vgg-verydeep-19.mat) and should be placed in the top level of the repository. In case you wish to specify a different location then use the `--network` flag.  
  
  __Dependencies__
  
  ```
  numpy
  Pillow
  scipy==1.1
  tensorflow-gpu >=1.0, <2.0 # works for cpu as well
  ```
  
  # Results  
  
  <p align="center"><img src="plots/1.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="plots/2.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="plots/3.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="plots/4.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="plots/5.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="plots/6.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="plots/7.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="plots/8.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="plots/9.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="plots/10.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="plots/11.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="plots/12.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="plots/13.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="plots/15.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="plots/16.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="plots/17.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="plots/18.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="plots/19.png" height="100" width="150"></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="plots/20.png" height="100" width="150"></img>  

# Citation
If you use this implementation in your work then please cite the following:
```
@misc{karush17neuralart,
  author = {Karush Suri},
  title = {Neural Art},
  year = {2020},
  howpublished = {\url{https://github.com/karush17/Neural-Art-Tensorflow}},
  note = {commit xxxxxxx}
}
```  

# References  
1. [A Neural Algorithm of Artistic Style](https://arxiv.org/pdf/1508.06576v2.pdf)  
2. [PyTorch Implementation](https://github.com/animesh-s/Neural-Style-Transfer)
3. [Medium Blog Post](https://towardsdatascience.com/a-neural-algorithm-of-artistic-style-a-modern-form-of-creation-d39a6ac7e715)
4. [Notes on Variational Denoising](https://en.wikipedia.org/wiki/Total_variation_denoising)

 
# License  
Copyright 2020 Karush Suri. Released under MIT License. See [LICENSE](https://github.com/karush17/Neural-Art-Tensorflow/blob/master/LICENSE) for details. 
  
  
  




