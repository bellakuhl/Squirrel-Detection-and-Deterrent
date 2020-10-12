# Squirrel Detection and Deterrent
# The goal of this project is to create a system that can detect and humanely discourage squirrels and bird from eating or digging up my plants.

| Requirements   	| Method                	| Notes                                                                                                                                                                                     	|   	|   	|
|----------------	|-----------------------	|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|---	|---	|
| Deter humanely 	| Water                 	| DC water pump, mounted close to plants, pulls from bucket                                                                                                                                 	|   	|   	|
| Detect animals 	| Tensorflow Lite, RPi4 	| Version 1 will use sample model that can detect 80 common objects - Classifies squirrel as cat/dog, classifies bird and human correctly - Will have water shoot if any animal is detected 	|   	|   	|
| Waterproof     	| 3D printing           	| A custom box for electrical and mechanical parts will be waterproofed                                                                                                                     	|   	|   	|
## Sources:

1) Check CUDA, cudNN, and Tensorflow capabilties: https://www.tensorflow.org/install/source#linux
2) Guide for installing Tensorflow Lite onto RPi: https://www.youtube.com/watch?v=aimSGOAUI8Y&ab_channel=EdjeElectronics
