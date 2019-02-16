# Computer-Vision-I

Here is CS537 computer vision 1 for OSU class

In project 2
->I use the decriptor.ipnb and CNN3 which is provide from TA. 
->Then get the des for each 35 and 140 images.(SIFT and SURF)
  therefore, the size of 35(Query) is 35*30 the size of 140(image) is 140*30 
  then save them to a pt file
->using one to one method 
  ->find the dist
  ->find sim
  ->using Hungarian algorithm find [0 1]matrix
  ->match the sim and [0 1]matrix
  ->sum
->using many to many method 
  ->dist
  ->sim
  ->norm
  ->Regular= sim/norm ==>[0,1]
  ->sum sim
->TN,TP,FN,FP
