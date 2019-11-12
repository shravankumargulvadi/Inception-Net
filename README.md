# Inception Network
## EVA Assignment-7
This repository contains the contents of EVA Assignment 7


|Layers       |Kernel|Padding|Stride|Channel_in|Channel_out|Jump|Receptive Field|
|-------------|------|-------|------|----------|-----------|----|---------------|
|Input        |      |1      |1     |224       |224        |1   |1              |
|Conv         |7     |3      |2     |224       |112        |1   |7              |
|MaxPool      |3     |1      |2     |112       |56         |2   |11             |
|Conv         |3     |1      |1     |56        |56         |4   |19             |
|MaxPool      |3     |1      |2     |56        |28         |4   |27             |
|Inception(3a)|5     |2      |1     |28        |28         |8   |59             |
|Inception(3a)|5     |2      |1     |28        |28         |8   |91             |
|MaxPool      |3     |1      |2     |28        |14         |8   |107            |
|Inception(4a)|5     |2      |1     |14        |14         |16  |171            |
|Inception(4b)|5     |2      |1     |14        |14         |16  |235            |
|Inception(4c)|5     |2      |1     |14        |14         |16  |299            |
|Inception(4d)|5     |2      |1     |14        |14         |16  |363            |
|Inception(4e)|5     |2      |1     |14        |14         |16  |427            |
|MaxPool      |3     |1      |2     |14        |7          |16  |459            |
|Inception(5a)|5     |2      |1     |7         |7          |32  |587            |
|Inception(5b)|5     |2      |1     |7         |7          |32  |715            |
|AvgPool      |7     |0      |1     |7         |1          |32  |907            |

