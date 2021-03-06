# EPSIF
The code is associated with the following paper:

Ryo Abiko, and Masaaki Ikehara. "Fast Edge Preserving 2D Smoothing Filter Using Indicator Function." ICASSP 2019-2019 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, 2019.


|Input image|Smoothed image|
|:--:|:--:|
|<img src="images/bird.png" width=70%>|<img src="images/smoothed_image.png" width=70%>|

## Requirements
- MATLAB
- C, C++ compiler

## Setup
Our code is based on MATLAB.
Since we use mex file, you need to compile first.

run `compile_mex.m` to compile c++ files.

## Usage
run `demo.m`

## Citation
Please cite this paper if you use this code. 

```
@inproceedings{abiko2019fast,
  title={Fast Edge Preserving 2D Smoothing Filter Using Indicator Function},
  author={Abiko, Ryo and Ikehara, Masaaki},
  booktitle={ICASSP 2019-2019 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  pages={1877--1881},
  year={2019},
  organization={IEEE}
}
```


For further information, please contact: {abiko, ikehara}@tkhm.elec.keio.ac.jp


