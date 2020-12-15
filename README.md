# (tensorflow)-ABNE-An-Attention-Based-Network-Embedding-for-User-Alignment-Across-Social-Networks


#  For wider application, we have updated the python version，use tensorflow1.14.0

ABNE-An-Attention-Based-Network-Embedding-for-User-Alignment-Across-Social-Networks(IEEE 2019)
paper author uses Java(https://github.com/ColaLL/IONE) 

Source Code and anonymous twitter_foursquare data for IEEE 2019 paper "ABNE-An-Attention-Based-Network-Embedding-for-User-Alignment-Across-Social-Networks (Liu Li liuli0407@hotmail.com) when you have any problems about the paper or the code(Java 8).

Feel free to contact me (Zihan Yan yzhcqupt@163.com) when you have any problems about the code(Python tensorflow1.14.0)

#1./For the ABNE, run the _main_.py.

#2./Second, run _Attention_.py to get attention.

#3./then,  run acc.py to get accuracy.

If you want to use another social network, pls modify the parameter size of the network,Here is twitter(5120),foursquare(5313).
Experimental comparison：(We have done a number of experiments and take the average value such as train ratio10%, p@1-p@30)


time in other experiments:  
java:  56min 
tensorflow-gpu(1.14.0): 27min   

Accuracy in other experiments：+0.004 ~ +0.012
