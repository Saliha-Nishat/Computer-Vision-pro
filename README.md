The Expression in-the-Wild (ExpW) dataset contains a diverse collection of face images labeled with various facial expressions, collected from unconstrained, real-world conditions. It is designed to support research and development in facial expression recognition.

Dataset Overview
Total Images: 91,793
Expression Categories: Happiness, Sadness, Anger, Surprise, Fear, Disgust, Neutral
Diversity: Includes variations in age, gender, ethnicity, lighting, background, and face poses, representing natural real-world scenarios.

File Structure
images/: Contains all face images labeled with corresponding expressions.
labels.csv: Includes image filenames with their associated expression labels.
Expression Labels
Label	   Description
0       	Neutral
1       	Happiness
2       	Sadness
3       	Surprise
4	        Fear
5       	Disgust
6       	Anger
Getting Started
To use the dataset, simply clone or download this repository and extract the files. The images can be used directly for training, validation, and testing of facial expression recognition models.

Citation

@inproceedings{zhang2018facial,
  title={Facial expression recognition in the wild: A new dataset and deep recognition},
  author={Zhang, Zhanpeng and Luo, Ping and Loy, Chen Change and Tang, Xiaoou},
  booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition},
  year={2018}
}

