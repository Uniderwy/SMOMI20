# SMOMI20
В этой задаче используется полносвязная нейронная сеть из шести слоев: один Flatten и пять Dense. В первых четырёх слоях Dense используется активация selu, в последнем linear. В слоях Dense 64, 64, 64, 64 и 10 нейронов соответсвенно.

В цикле обучения используется оптимизатор Adam, функция потерь SparceCategoricalCrossentropy и метрика accuracy. 
Всего производится 20 эпох обучения.
Итоговая точность: 0.4498.

Для получения графиков был использован Tensorboard.

Графики функции потерь:
(https://github.com/uniderwy/SMOMI20/raw/master/image/epoch_acc.jpg)
(https://github.com/uniderwy/SMOMI20/raw/master/image/epoch_loss.jpg)

Графики метрики точности:
(https://github.com/uniderwy/SMOMI20/raw/master/image/epoch_val_acc.jpg)
(https://github.com/uniderwy/SMOMI20/raw/master/image/epoch_val_loss.jpg)
