# xtract-features = 0.0.1

#### Introduction:
This package is developed to extract **GLCM**, **Region Properties**, and **Moments** related features in a line of code and then get those into a _data-frame_. This package only works for _**two channel**_ _grayscale_ images and generally is developed to extract features from X-ray images. The package isn't currently available on **PyPi** or **Anaconda** because more CBIR based features will be added to this package.  

## Installing the package:
The package is tested on _**python3**_ and is working as required. You need to have python3 in your systems. Use the following commands to get started with the package.

```
sudo apt-get update

sudo apt-get install python3-dev python3-pip
 
pip3 install git+https://github.com/vatsalsaglani/xrayimage_extractfeatures.git

```

## Getting Started:

##### The package is divided into six modules.

1. __Helpers__
	- Extract-img-array
	- Save Pickle
	- Load Pickle
	- Show
	- Plots
2. __Feature Extraction__
	- Shannon's Entropy
	- Simple Entropy
	- Feature Dictionary from Image Path
	- Feature Dictionary from Image Array
	- Get dataframe form Image Path
	- Get dataframe from Image Array
3. __GLCM Features__
	- Correlation
	- Homogeneity
	- Energy
	- Contrast
	- All GLCM Features
4. __Moments__
	- 24 Variant Moments
	- 7 Hu Moments
5. __Region Properties__
	- 27 Region Properties functions
6. __Extras__
	- 2D Convolutions
	- Segmentation

## Helpers

![Import Helpers](images/helpers1.png)
![extract-img-array](images/helpers2.png)
![extract-img-array without getID](images/helpers3.png)
![show function](images/helpers4.png)
![plots with titles](images/helpers7.png)
![plots without titles](images/helpers8.png)
![save any data inside a variable](images/helpers5.png)
![load the saved data](images/helpers6.png)


## Feature Extraction

![intro](images/extract1.png)
![feature dictionary](images/extract2.png)
![dict](images/extract2_op.png)
![without ids or names](images/extract3.png)
![output without ids](images/extract3_op.png)
![dict from img array](images/extract4.png)
![output of the above](images/extract4_op.png)
![extract dataframe from path](images/extract_df_path.png)
![extract dataframe from img array](images/extract_df_numpy_array.png)
<br><br>


## GLCM Features

![glcms](images/glcm.png)
![glcmall](images/glcm_all.png)
<br><br>


## Moments

![24 moments](images/moments.png)
![hu moments](images/moments_hu.png)
<br><br>


## Region Properties

![region props 1](images/region_props1.png)
![region props 2](images/region_props2.png)
![region props 3](images/region_props3.png)
<br><br>


## Extras

### 2D Convolutions

![2d Conv](images/conv2d.png)
<br><br>

### Segmentation

![watershed segmentation](images/seg.png)


**Fork the repo and install it and test it through various types of X-Ray images and put it through its paces and lets discuss some issues if present.**

