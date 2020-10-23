# SegmentalDTW

This repository contains the code for the paper "Segmental DTW: A Parallelizable Alternative to DTW."

The goal of this project is to globally align two feature sequences with a parallelizable algorithm.

Simply clone the virtual environment and run the jupyter notebooks in order.  Because the second notebook takes a long time to run, you can also run it from the command line with:

`jupyter nbconvert --to notebook --execute --inplace --ExecutePreprocessor.enabled=True --ExecutePreprocessor.timeout=-1 02_Align.ipynb`
