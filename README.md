# Mini-Project-DL
![Resnet](resnet.png)

Original model's parameters list:

| Block  |      No of Conv2d Layers  |        C<sub>in</sub>       |   F<sub>in</sub>   | K<sub>in</sub> | P | 
| :---           | :----:   |    :----:        |      :----:      |   :----:  |      ---:          |
| Conv1| |  1 Conv2d              |                      | 
|     layer1             |    4 Conv2d                 |               |                      |
|     layer2             |    4 Conv2d                 |               |                      |
|     layer3             |    4 Conv2d                 |               |                      |
|     layer4             |    4 Conv2d                 |               |                      |
|     linear             |    1 linear layer          |                |                      |



We tried the following sets of hyperparameters for 100 epochs each.


| Block  |      No of Conv2d Layers  |        C<sub>in</sub>       |   F<sub>in</sub>   | K<sub>in</sub> | P | Learning rate | OPtimizer | epochs| Validation accuracy  |
| :---               |      :----:         |   :----:      |        :----:       | :----:   |    :----:        |      :----:         |   :----:      |   :----:  |      ---:          |
| Conv1| |  1 Conv2d              |                      | 
|     layer1             |    4 Conv2d                 |               |                      |
|     layer2             |    4 Conv2d                 |               |                      |
|     layer3             |    4 Conv2d                 |               |                      |
|     layer4             |    4 Conv2d                 |               |                      |
|     linear             |    1 linear layer          |                |                      |
