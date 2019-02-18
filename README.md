# Protein-Recognition
This Program has two Parts:

## 2D Model Recognition:
You can run the 2D Model Recogniton using GeometricHashing2D.py file.

The program is prepared to recognize Triangle and square models, however
you can add any model that you want to train the program to recognize in 
"Models2D" folder with the name "model_#".

The program has one test case ,however you can add any test case
in "test scenes" folder with the name "test_#".Then, you need to update

the index of test file in GeometricHashing2D file line 423.
test_file = open('test scenes/test_' + str(0) + '.txt', 'r')


## 3D Model Recognition:

You can run the 3D Model Recogniton using GeometricHashing3D.py file.

The program is prepared to recognize 10 protein interfaces, however
you can add any interface from PIFACE website that you want to train the program to recognize in 
"Models3D" folder with the name "model_#".
