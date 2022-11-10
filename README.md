# Foggy-DOTA

Official release of "Foggy-DOTA: An Adverse weather Dataset for Object detection in Aerial images"

The dataset published at the [NICS2022](http://nafosted-nics.org/)

Presentation: [Youtube](https://www.youtube.com/watch?v=k6dgxdbHYKo&t=212s)

Presenter: [Phuc Nguyen Duc Anh](https://github.com/PhucNDA)

Materials: [Slide](Foggy-DOTA-NICS.pdf)

Paper: not yet published
# Introduction
Nowadays, object detection in aerial images in adverse weather, especially in foggy scenes becoming very challenging and incredibly practical. Furthermore, fog and clouds usually appear in the majority of aerial images captured via drones everywhere on Earth, especially in the early morning. Understanding the need for qualified deep learning approaches, we propose a Foggy-DOTA dataset inheriting from the original DOTA dataset and then empirically evaluate it on multiple State-of-the-art methods. After having conducted lots of experiments on some well-known baselines,  ReDet is the highest method achieving 76.680 mAP on the original DOTA, only 74.194 mAP on our Foggy-DOTA dataset (60.706 mAP if trained on DOTA). On the other hand, S2ANet and RoI Transformer achieve 74.190, 76,09 mAP on the original DOTA, only yield 71.629 and 73.381 mAP on our Foggy-DOTA dataset (46.503 and 40.297 mAP - significantly low if trained on DOTA), respectively. Our work provides comprehensive statistical evaluation being an essential baseline for future object detection research.

Some figures in the dataset:
<p>
    <img src="Visualization-Dataset/vis-data.png" alt="Sample Image Visualization Dataset" style="height: 100%; width: 100%;">
</p>

**For academic purposes, we provide neither the training weight nor oriented object detector**

**Also, for the synthetic fog generator, we consulted many experts and hand-designed the dataset, so there is no source code for it**

# Dataset
Foggy-DOTA mix the thin-fog and thick-fog sets. Choose your favorite mix.
* Train: [Thin](https://drive.google.com/file/d/1-QJXAfYm4-iQfGWNix0tJsew-TNnY7VA/view?usp=sharing) [Thick](https://drive.google.com/file/d/17JP2WFE6RnQUEF5WrD8LSC_Pw1N-AwKR/view?usp=share_link)
* Validate: [Thin](https://drive.google.com/file/d/1-G_YlzNwxb3eR1yIv8_I2RupM-HzWPsB/view?usp=share_link) [Thick](https://drive.google.com/file/d/1-27KeQDTFpc0_PTQxeOKzunTMbuC4WC-/view?usp=share_link)
* Test: [Thin](https://drive.google.com/file/d/1-NWaDWkZIJlDHwSdQvuCoMiVPzX1m2Pn/view?usp=share_link) [Thick](https://drive.google.com/file/d/1NitesYDXuFxCp6oJtUI1nrVCXWUkJuOg/view?usp=share_link)

<p>
    <img src="Visualization-Detection/vis-detection.png" alt="Sample Image Visualization Dataset" style="height: 100%; width: 100%;">
</p>
