# Vanet
Designing Vehicular Ad-hoc Networks using Random Forest Technique of Machine Learning
Abstract-VehicularAd-hocNetworksarecreatedbyapplyingtheprinciplesofmobileadhocnetworks(MANETs) thespontaneouscreation ofawirelessnetworkfordataexchange tothedomainofvehicles.Itwas shown that vehicle-to-vehicle and vehicle-to-roadside communications architectures will co-exist in VANETs to provide road safety, navigation, and other roadside services. VANETs are a key part of the intelligent transportation systems (ITS) framework. Sometimes, VANETs are referred as Intelligent Transportation Networks.In this study, our mainaimtoproceedwithVANET’sanddesigningthemusingRandom Forest Technique of Machine Learning.We summarize proposing how Random Forest Algorithm can be easily implemented to ensure Road safety. 

# DATASETS 
#1 No. of Vehicle Trees 
It is true that generally more trees will result in better accuracy. However, more trees also mean more computational cost and after a certain number of trees the improvement id negligible.

#2 Max depth of the Vehicle 
Trees max depthrepresents the depth of each tree in the forest. Deeper the tree, the more splits it has and thus captures more information about the data. The depth of VANET tree depends onthenumberofvehicularinformation weincludeinourtree.

#3 Minimum Sample Split for Vehicle Tree 
min samples splitrepresents the minimum number of sample required to split an internal node. This can vary between considering at least one sample at each node to considering all of the samples at each node. The split sample includes the features we are including in Vehicular tree. The sample required to split internal node of VANET tree includes the position of vehicles, speed of vehicles, trafﬁc condition, accuracy of position etc ...

#4 Minimum Sample Leaf for Vehicular Tree 
min sample leafis the minimum number of samples required to be at leaf node. This parameter is similar to min sample split. However, this describes the minimum number of samples at the leafs, the base of the Vehicular tree. The leaves decide the ﬁnal outcome of classiﬁer tree whether the position of vehicle is accurate or not.

#5 Number of Random Features of Vehicular Tree 
max features represents the numbers to consider when looking for the best split. Some features considered are current GPS position and the speed of the car, distance, between car and trafﬁc condition.
