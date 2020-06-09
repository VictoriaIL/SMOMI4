# SMOMI4




В данной лабораторной работе необходимо было использовать различные методы аугментации при обучении сети. Я использовала предобученную нейронную сеть VGG16 с обученным классификатором.
 
### 1) Горизонтальное отражение


![.](https://github.com/VictoriaIL/SMOMI4/blob/master/flip/A_train_flip.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/flip/L_train_flip.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/flip/A_val_flip.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/flip/L_val_flip.PNG)



### 2) Поворот на случайный угол


#### a. 10 градусов 


![.](https://github.com/VictoriaIL/SMOMI4/blob/master/rotate/A_train_10.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/rotate/L_train_10.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/rotate/A_val_10.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/rotate/L_val_10.PNG)


#### b. 60 градусов 


![.](https://github.com/VictoriaIL/SMOMI4/blob/master/rotate/A_train_60.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/rotate/L_train_60.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/rotate/A_val_60.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/rotate/L_val_60.PNG)


#### c. 90 градусов 


![.](https://github.com/VictoriaIL/SMOMI4/blob/master/rotate/A_train_90.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/rotate/L_train_90.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/rotate/A_val_90.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/rotate/L_val_90.PNG)


### 3) Изменение яркости


#### a. Коэффициент 0.4


![.](https://github.com/VictoriaIL/SMOMI4/blob/master/bright/A_train_(0.4).PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/bright/L_train_(0.4).PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/bright/A_val_(0.4).PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/bright/L_val_(0.4).PNG)


#### b. Коэффициент 0.3


![.](https://github.com/VictoriaIL/SMOMI4/blob/master/bright/A_train_0.3.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/bright/L_train_0.3.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/bright/A_val_0.3.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/bright/L_val_0.3.PNG)


#### c. Коэффициент 0.5


![.](https://github.com/VictoriaIL/SMOMI4/blob/master/bright/A_train_(0.5).PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/bright/L_train_(0.5).PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/bright/A_val_(0.5).PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/bright/L_val_(0.5).PNG)


### 4) Выделение случайного участка изображения


#### a. 130x130


![.](https://github.com/VictoriaIL/SMOMI4/blob/master/crop/A_train_crop_130.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/crop/L_train_crop_130.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/crop/A_val_crop_130.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/crop/L_val_crop_130.PNG)


#### b. 170x170


![.](https://github.com/VictoriaIL/SMOMI4/blob/master/crop/A_train_crop_170.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/crop/L_train_crop_170.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/crop/A_val_crop_170.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/crop/L_val_crop_170.PNG)


#### c. 200x200


![.](https://github.com/VictoriaIL/SMOMI4/blob/master/crop/A_train_crop_200.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/crop/L_train_crop_200.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/crop/A_val_crop_200.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/crop/L_val_crop_200.PNG)

#### d. 215x215

![.](https://github.com/VictoriaIL/SMOMI4/blob/master/crop/A_train_crop_215.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/crop/L_train_crop_215.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/crop/A_val_crop_215.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/crop/L_val_crop_215.PNG)

###  5) Итоговая аугментация с наилучшими параметрами

degree = 10
brightness 0.5
crop 215x215

![.](https://github.com/VictoriaIL/SMOMI4/blob/master/final/A_train_final.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/final/L_train_final.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/final/A_val_final.PNG)![.](https://github.com/VictoriaIL/SMOMI4/blob/master/final/L_val_final.PNG)
