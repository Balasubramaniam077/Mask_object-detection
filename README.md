<!DOCTYPE html>
<html>
    <h1><u>Pandamic Mask Object Detection</u></h1>
    <h2>Introduction</h2>
    <p>Wearing face masks is recommended as part of personal protective equipment and as a public health measure to prevent the spread of coronavirus disease 2019 (COVID-19) pandemic. Their use, however, is deeply connected to social and cultural practices and has acquired a variety of personal and social meanings. This article aims to identify the diversity of sociocultural, ethical, and political meanings attributed to face masks, how they might impact public health policies, and how they should be considered in health communication. In May 2020, we involved 29 experts of an interdisciplinary research network on health and society to provide their testimonies on the use of face masks in 20 European and 2 Asian countries (China and South Korea). They reflected on regulations in the corresponding jurisdictions as well as the personal and social aspects of face mask wearing. We analyzed those testimonies thematically, employing the method of qualitative descriptive analysis. The analysis framed the four dimensions of the societal and personal practices of wearing (or not wearing) face masks: individual perceptions of infection risk, personal interpretations of responsibility and solidarity, cultural traditions and religious imprinting, and the need of expressing self-identity. Our study points to the importance for an in-depth understanding of the cultural and sociopolitical considerations around the personal and social meaning of mask wearing in different contexts as a necessary prerequisite for the assessment of the effectiveness of face masks as a public health measure. Improving the personal and collective understanding of citizens' behaviors and attitudes appears essential for designing more effective health communications about COVID-19 pandemic or other global crises in the future. </p>
    <h3><u>My Solution</u></h3>
    <p>My solution I used the Deep Learning Model for object Detection(It can localization the object in an Frames).In computer vision we use to CCVT camera for Live feed of the video. I Used two Deep Leaning Best Object detection models are YOLOV4 (DARKNET-53)  || YOLOV5 (v5 s - 7.3M params) and I used Raspberry Pi 3 (Model B+) for the Mask Detection </p>
    <h4><u><b>Dataset</b></u></h4>
    <p>My Dataset classes are Mainly three there are :</p>
    <p><b>-->with_mask</b></p>
    <p><b>-->wihtmask_incorrect</b></p> 
    <p><b>-->without_mask</b></p>
    <p>I using  the open datasets in Kaggle for the main 2 classes.There are "with_mask" and  "without_mask"</p>
    <p>At the time i cannot get the other class for my solution that is mask incorrect position Dataset.So i am created the own an custom dataset for the class of wihtmask_incorrect position. I share the my collected custom dataset in my  <a href="https://drive.google.com/drive/folders/1zk9HYyKZD7Klu2l4pX1m03AqB6OO9ibw?usp=sharing">Drive Link</a> or Refer my dataset in <a href="https://www.w3schools.com">Kaggle!</a></p>
<h4> Model selection </h4>
<p>First off i Used the Yolov4 - Tiny in Darknet53 Framework.It has an amazing speed and Accuracy because it has a low parameters in base model of darknet Framework.</p>
<p>After finish the Darknet Yolov4 - Tiny Model. I has been Seen the YOLO V5 model it has an amazing model compare to the Yolo V4 tiny.At time i suddenly move to yolov5 Small model.</p>
<h4>Architecture</h4>
<img src="https://github.com/Balasubramaniam077/Mask_object-detection/blob/main/scr/yolov4-tiny%20.png" alt="yolov4-tiny" align="center">
<p align="center">YoloV4-TINY Architecture</p>
<img src="https://github.com/Balasubramaniam077/Mask_object-detection/blob/main/scr/yolov5.png" alt="yolov4-tiny" align="center">
<p align="center">YoloV5 Architecture</p>
    
<p>In Improment of YOLOV5 is coming soon with very ligth model in pytorch</p>
</html>
