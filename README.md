# GFresNet
A deep learning database and network for focusing guided wave defect detection 
Since the paper is being submitted, the database set will be published after the paper is accepted.
Database set information:The defects are classified as three types and specimens with no defect are also included.
In the established database set, the defect depth ranges from 10% to 50%, with 10% intervals.
In addition, the radius of the pinhole defect ranges from 0.5 mm to 3 mm,
and the sizes of the crack defect range from 1×5 mm2 to 2×10 mm2,
and the sizes of the corrosion defect range from 5×5 mm2 to 10×10 mm2.
Each defect contains 1500 signal data, and the ratio of the training,
validation, and test data sets are divided into 6:2:2 in this work. The data storage format and
explain the descriptive data (take the pinhole defect signal with a radius of 3 mm and a depth of 10% as an example).
The data set has a total of 48,060,000 signal value data and contains detailed information about defects.

No.	1	2	3	4	5	6	7	8	9	10	11	12	13	14	···
Data	-1	1	0	0	3	10	0	0	0	-2	0	0	0	0	···

Title: Development of frequency-mixed point-focusing shear horizontal guided wave EMAT for defect inspection using deep neural network
Author: Hongyu Sun, State Key of Power Systems, Department of Electrical Engineering, Tsinghua University, Beijing, 10084, China.
Email: sunhy18@mails.tsinghua.edu.cn

If you use our code and database set, please cite our paper [however, not published].

NOTICE:Reviewers can obtain the data set password from the end of the paper to run the code.

Development environment：
TensorFlow 2.2
CUDA 10.1
Python 3.7
