# UAV-based-Transport-Management-System
Designed a multi-stage architecture combining Improvised YOLOv8 for object detection and category-specific modified Vision Transformer models for severity classification, achieving high detection accuracy and 92% severity classification precision.  

**Dataset:** <br>
UAV images are the considered for this project. There are 6 obstacle categories which are considered as highest priority in this project. For eahc of these obstacles, data in the form of images and videos is collected. The combined dataset which is passed to Stage 1 modelling consists of more than 1 million images.

**Frontend:** <br>
I have designed about 11 dashboards for the system design, which includes login page, Category-specific severity pages and Homepage
Designs can be easily imported from the below link
https://www.figma.com/design/mXp8MYmNrHkmmlKdyOixGX/Transport_Management_System?node-id=0-1&p=f&t=BsFB1vPyoHwhErpZ-0

**Modelling:** <br>
Designed a 2 stage modelling for this project. <br>
**Stage 1** involves Obstacle detection- Improvised Yolov8 is used in this stage<br>
**Stage 2** Severity classification of the detected obstacle is shown in this stage where the severity classes are low, medium and high. In total 6 severity models are built. Each model is trained on the repsective obstacle-dataset
For stage 2 modelling, Vision transformer is choosen as the base model, it is then modified and improvised at different levels of the architecture and then combined with stage 1 modelling for the overall dataflow.
Severity classification is done based on the Area and count of the respective obstacles<br>

I have choosen 3 obstacles out of 6 and made the respective severity models.

For the modelling architecure diagrams and other diagrams present in the PPT and Document, I have used [Lucid chart](https://www.lucidchart.com/pages/)
