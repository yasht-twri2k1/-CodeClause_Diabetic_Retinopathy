# CodeClause_Diabetic_Retinopathy
Diabetic retinopathy is the leading cause of blindness in the working-age population of the developed world. It is estimated to affect over 93 million people.

![image](https://user-images.githubusercontent.com/84243553/196471053-5f71ef54-a0a0-45c8-85b5-275ba705cdd1.png)


The US Center for Disease Control and Prevention estimates that 29.1 million people in the US have diabetes and the World Health Organization estimates that 347 million people have the disease worldwide. Diabetic Retinopathy (DR) is an eye disease associated with long-standing diabetes. Around 40% to 45% of Americans with diabetes have some stage of the disease. Progression to vision impairment can be slowed or averted if DR is detected in time, however this can be difficult as the disease often shows few symptoms until it is too late to provide effective treatment.

Currently, detecting DR is a time-consuming and manual process that requires a trained clinician to examine and evaluate digital color fundus photographs of the retina. By the time human readers submit their reviews, often a day or two later, the delayed results lead to lost follow up, miscommunication, and delayed treatment.

Clinicians can identify DR by the presence of lesions associated with the vascular abnormalities caused by the disease. While this approach is effective, its resource demands are high. The expertise and equipment required are often lacking in areas where the rate of diabetes in local populations is high and DR detection is most needed. As the number of individuals with diabetes continues to grow, the infrastructure needed to prevent blindness due to DR will become even more insufficient.

The need for a comprehensive and automated method of DR screening has long been recognized, and previous efforts have made good progress using image classification, pattern recognition, and machine learning. With color fundus photography as input, the goal of this competition is to push an automated detection system to the limit of what is possible – ideally resulting in models with realistic clinical potential. The winning models will be open sourced to maximize the impact such a model can have on improving DR detection.

<h1>Solution To Diabetic Retinopathy Detection </h1>
 <h3>
 <ul>
 <li>RED DOTS(microaneurysms)</li>
 <li>YELLOW "FLAKES"</li>
 <li>INCREASE IN BLOOD VESSEL</li>
 </ul>
 </h3>
 <br>
 <h2>DATASET DESCRIPTION</h2>
 You are provided with a large set of high-resolution retina images taken under a variety of imaging conditions. A left and right field is provided for every subject. Images are labeled with a subject id as well as either left or right (e.g. 1_left.jpeg is the left eye of patient id 1).

A clinician has rated the presence of diabetic retinopathy in each image on a scale of 0 to 4, according to the following scale:
 <h3>
 <ol>
 <li>NO DR -"0"</li>
 <li>MILD -"1"</li>
 <li>MODERATE -"2"</li>
 <li>SEVERE -"3"</li>
 <li>PROLIFERATIVE -"4"</li>
 </ol>
 </h3>

Your task is to create an automated analysis system capable of assigning a score based on this scale.

The images in the dataset come from different models and types of cameras, which can affect the visual appearance of left vs. right. Some images are shown as one would see the retina anatomically (macula on the left, optic nerve on the right for the right eye). Others are shown as one would see through a microscope condensing lens (i.e. inverted, as one sees in a typical live eye exam). There are generally two ways to tell if an image is inverted:

It is inverted if the macula (the small dark central area) is slightly higher than the midline through the optic nerve. If the macula is lower than the midline of the optic nerve, it's not inverted.
If there is a notch on the side of the image (square, triangle, or circle) then it's not inverted. If there is no notch, it's inverted.
Like any real-world data set, you will encounter noise in both the images and labels. Images may contain artifacts, be out of focus, underexposed, or overexposed. A major aim of this competition is to develop robust algorithms that can function in the presence of noise and variation.

<h1>Approach To Diabetic Retinopathy Detection </h1>
<h3>CODE :https://colab.research.google.com/drive/1G8KDqzCtdEX8MtfGjYLLFCKERanoZwg9?usp=sharing</h3>
<h3>MODEL :CNN ALGORITHM</h3>
<h3>PLATFORM :GOOGLE COLLAB</h3>
<h3>DATASET :KAGGLE</h3>
<h3>THANK YOU!</h3>

