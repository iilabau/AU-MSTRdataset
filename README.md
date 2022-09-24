
## AU-MSTR: A Multi-script Scene Text Reading Dataset

A multi-script indoor-outdoor scene image dataset is developed for text detection, referred to as Aliah University-Multi-script Scene Text Reading (AU-MSTR) dataset.
Digital cameras built in handheld devices such as cellphones, smart phones, portable digital assistants (PDAs), etc. are used for preparation of this dataset due to its fast and easy image acquisition capability under unconstrained environments.Images are captured under unconstraint environment using multiple cameras with varying focal length that generates perpective distorted image. Images are also captured in day-light and night, that certainly augment additional challenges for scene text detection.

In the developed dataset, word-level annotation is prepared for multi-script text detection. Each word is enclosed by bounding box to generate corresponding GT. GT bounding boxes are specified by the coordinates of four corner points of boxes in clock-wise direction as {x1,y1},{x2,y2},{x3,y3},{x4,y4}. GT file is prepared using .txt format, where for each image a corresponding text file is prepared. Now, within each GT file, each row of coordinates represents a GT bounding box. GT file is prepared for both training and test set separately. 

### Dataset Summary

Images of AU-MSTR dataset are captured in indoor as well as outdoor environments. Indoor images are mainly captured from bottles, pens, packets, other household accessories etc. whereas outdoor scene images are captured from poster, banner, traffic sign-boards, wall paintings, buildings and other real-life sources. This dataset comprises of a total of 569 scene text images acquired with cell-phone cameras of different resolutions, highest being 12 megapixels. Total images are divided into 2:1 ratio for training and testing. This dataset is comprised of four classes of scripts viz. Latin, Devanagari, Bengali, and Mixed. Image of mixed class are embedded with texts of more than one scripts out of three scripts. A brief outline of AU-MSTR dataset with script-wise image distribution is shown below:

Script:
  1. Latin: Train set-121, Test set-61, Total-182
  2. Bengali: Train set-75, Test set-37, Total-112
  3. Devanagari: Train set-89, Test set-44, Total-133
  4. Mixed: Train set-94, Test set-48, Total-142
  
Total train images -379, Total test images-190, Total images-569


### Relevant Paper
The following paper may be consulted and cited while referring to this dataset.
> **Khan, T. and Mollah, A.F., 2022. A Novel Multi-scale Deep Neural Framework for Script Invariant Text Detection. Neural Processing Letters, 54(2), pp.1371-1397.**

### Contributors
- Mr. Tauseef Khan, Senior Research Fellow, Department of Computer Science and Engineering, Aliah University, IIA/27 NewTown, Kolkata 700160, India
- Dr. Ayatullah Faruk Mollah, 
Department of Computer Science and Engineering, 
Aliah University, India

### Contact
Mr. Tauseef Khan, Email: tauseef.hit2013@gmail.com
