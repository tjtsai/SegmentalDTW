# SegmentalDTW

This repository contains the code for the ICASSP 2021 paper "Segmental DTW: A Parallelizable Alternative to Dynamic Time Warping."

The goal of this project is to globally align two feature sequences with a parallelizable algorithm.

You can find the paper [here](https://drive.google.com/file/d/19WMEP3cayMQnnywa1eufTnukTrEK4ec5/view?usp=sharing).

Simply clone the virtual environment and run the jupyter notebooks in order.  Because the second notebook takes a long time to run, you can also run it from the command line with:

`jupyter nbconvert --to notebook --execute --inplace --ExecutePreprocessor.enabled=True --ExecutePreprocessor.timeout=-1 02_Align.ipynb`


## Citation

TJ Tsai. "Segmental DTW: A Parallelizable Alternative to Dynamic Time Warping" in Proceedings of the IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP), 2021, pp. 106-110.




### Acknowledgments

This material is based upon work supported by the National Science Foundation under Grant No. 1948531.  Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.
