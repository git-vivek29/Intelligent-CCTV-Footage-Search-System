# Intelligent-CCTV-Footage-Search-System

This project proposes intelligent searching of CCTV footage with an added module of Machine Learning. The system takes suspect image as an input and searches the suspect in CCTV footage by considering the parameter such as appearance of suspect and facial orientation features using machine learning. The system will return the position of suspect in CCTV footage video reel with highlighted suspect figure timestamp when the suspect was identified in CCTV footage. Various algorithms are reviewed and planned to use the following algorithms like Haar cascade for face detection and CNN and one shot learning method for face recognition and comparison.

## Architecture Diagram

![alt text](https://github.com/git-vivek29/Intelligent-CCTV-Footage-Search-System/blob/main/Architecture-Diagram.png "Architecture Diagram")

## Face cropped from suspect image (which is provided as input in suspect folder)

![alt text](https://github.com/git-vivek29/Intelligent-CCTV-Footage-Search-System/blob/main/face_crop/face_suspect1_0.jpg "face_suspect1_0")
![alt text](https://github.com/git-vivek29/Intelligent-CCTV-Footage-Search-System/blob/main/face_crop/face_suspect1_1.jpg "face_suspect1_1")

###### Note: Only single image of suspect is need to be added in suspect folder since system is implemented by single shot learning. 

## Frame captured with suspect highlighted (Frame is saved in output folder)
![alt text](https://github.com/git-vivek29/Intelligent-CCTV-Footage-Search-System/blob/main/output/img.jpg "Output Frame")

### Timestamp for frame at which suspect identified in CCTV footage is provided by output of python notebook file.

###### Note: Only first occurrence of suspect is saved and system terminates its task

[Please Download the vgg_face_weight.h5 file from here](https://drive.google.com/file/d/1h82obQ_LLQbZgEf9oxn0xNFDsmznKkb1/view?usp=sharing)

## For more information, please view the Research Paper published at International Research Journal of Engineering and Technology (IRJET)

[Click here for Published Research Paper](https://www.irjet.net/archives/V7/i4/IRJET-V7I4864.pdf)
