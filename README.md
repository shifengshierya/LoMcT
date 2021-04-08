# LoMcT
eBird; Mean-shift; LoMcT; multi-trajectory reconstruction; GAM; 
Here, we summarized the data, code, and necessary documents. We used Matlab and R as our tools, and the code were integrated them as a .mlapp named ” trajectory.mlapp” in the folder named “LoMcT” for ease of use. Anthus_spragueii.xlxs is one of the datasets we used in our manuscript. MeanShiftCluster.m can be invoked automatically when the” trajectory.mlapp” is running.

How to use “trajectory.mlapp” :
1.  Install the R language module in MATLAB, and install the MATLAB library in R.
2.  Change the path in. R file:
library("R.matlab")
setwd("C:/Users/ad/Desktop/guijitest")
to the corresponding path you use.
3.  Change the paths in MATLAB file:
Line 530 ：Rpath = 'D:\动物迁徙\拟合\R\R-3.6.3\R-3.6.3\bin'; %The R language installation path
Line 531 ：RscriptFileName ='.\XXXXX1.R'; %R file storage path
to the corresponding path you use.
4.   Then choose the dataset name “Anthus_spragueii”, press the operation button from top to bottom. (Be sure that you press the next button until “OK‘’ appears in the status box behind).
5.   Get the trajectories shown on the map finally.
