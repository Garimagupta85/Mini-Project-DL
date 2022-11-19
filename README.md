# Mini-Project-DL
![Resnet](resnet.png)

Original model's parameters list:

| Block          |      No of Conv2d Layers    |        C<sub>in</sub>       |   F<sub>in</sub>   | K<sub>in</sub> | P          |  
| :---           | :----:                      |    :----:                   |      :----:        |   :----:       |      ---:  |
| Conv1          | 1 Conv2d                    |       3                      |       64             |    3            |            |
|     layer1     |    4 Conv2d (1)               |       64                     |          64              | 3
|     layer1     |    4 Conv2d (2)              |       64                  |          64            | 3
|     layer1     |    1 Conv2d residual              |       64                    |        64              | 1
|     layer1     |    4 Conv2d (3)               |       64                     |     64                 | 3
|     layer1     |    4 Conv2d (4)              |       64                    |        64              | 3
|     layer1     |    1 Conv2d residual              |       64                    |        64              | 1
|     layer2     |    4 Conv2d (1)                |     64                        |             128         | 3
|     layer2     |    4 Conv2d  (2)               |     128                        |       128               | 3 
|     layer2    |    1 Conv2d residual              |      64                    |        128            | 1
|     layer2     |    4 Conv2d  (3)             |      128                        |      128                | 3
|     layer2     |    4 Conv2d  (4)           |         128                    |        128              |   3
|     layer2    |    1 Conv2d residual              |      128                   |        128           | 1
|     layer3     |    4 Conv2d                 |                             |                      |
|     layer4     |    4 Conv2d                 |                             |                      |
|     linear     |    1 linear layer           |                             |                      |



We tried the following sets of hyperparameters for 100 epochs each.


| Block  |      No of Conv2d Layers  |        C<sub>in</sub>       |   F<sub>in</sub>   | K<sub>in</sub> | P | Learning rate | OPtimizer | epochs| Test accuracy  |
| :---               |      :----:         |   :----:      |        :----:       | :----:   |    :----:        |      :----:         |   :----:      |   :----:  |      ---:          |
| Conv1| |  1 Conv2d              |                      | 
|     layer1             |    4 Conv2d                 |               |                      |
|     layer2             |    4 Conv2d                 |               |                      |
|     layer3             |    4 Conv2d                 |               |                      |
|     layer4             |    4 Conv2d                 |               |                      |
|     linear             |    1 linear layer          |                |                      |
