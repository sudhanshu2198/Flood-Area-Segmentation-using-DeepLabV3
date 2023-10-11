

# Flood Area Segmentation using DeepLabV3

Rapid urbanization, population growth, and extreme climate change have led to frequent flooding events, posing challenges for many countries around the world. The impacts of floods include loss of life, damage to property, and deterioration of health conditions.

![](https://i.ibb.co/gdXy4NB/opo.png)

One of major issue constraining disaster relief is 
- Lack of access to affected area.
- Flood effecting large expanse of area.
- Shortage of capabilities, infrastructure required for timely disaster relief.

Drone technoloy can play a pivotal role in timely humanitarian assistance delivery, gauging floods impacts and most affected areas. We will be using computer vision technique for segmenting flood area from images/video, that can be used for delivering assistance to non-flooded area like rooptops, determining the impact of flood.

**The main goal of this project is to develop a semantic segmentation model using DeepLabV3 architecture that can be used to segment flood water from the images/videos captured by drone.**

## 🔗 Links

- [Dataset](https://www.kaggle.com/datasets/faizalkarim/flood-area-segmentation)
- [Learned Model Weights](https://www.kaggle.com/code/sudhanshu2198/flood-area-segmentation-using-deeplabv3-pytorch/output?select=model.pth)
- [Kaggle Notebook](https://www.kaggle.com/code/sudhanshu2198/flood-area-segmentation-using-deeplabv3-pytorch/notebook)

## 🛠 Skills
Numpy, Matplotlib, Pandas, OpenCV, Pytorch, torchvision, albumentations

## Visualization
![](https://i.ibb.co/zSm0ZQf/op3.png)

## Results

**The model achieved a accuracy of 92% for correctly classifying the pixels as belonging to flooding or not.The model losses plateaued at around 50 epochs, and it ustilizes GPU Tesla P-100 for training taking 2.5 hours for training on the flood segmentation dataset containing 290 images.**

![](https://i.ibb.co/1zxyPZD/2.png)
![](https://i.ibb.co/9Nh4m27/3.png)





