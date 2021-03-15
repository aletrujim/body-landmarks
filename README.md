# body-landmarks
Human body landmarks with images segmented with [*BRemNet*](https://doi.org/10.3390/jimaging6090094)

<img src="results/C028-118_landmarks.jpg" width="200"/> <img src="results/C028-192_landmarks.jpg" width="200"/> <img src="results/C028-270_landmarks.jpg" width="200"/> 

## Installation
### Prerequisites
OpenCV
```
pip install opencv-python
```

### Install
Clone this repository:
```
git clone https://github.com/aletrujim/body-landmarks.git BodyLandmarks
```

## Dataset
The data used in this analysis were acquired with *BRemNet* (Background Removal Network) from [*body2vec*](https://doi.org/10.3390/jimaging6090094).
If you use this data or the method for acquiring your own segmented images dataset in your research, please cite this project.
```
@article{trujillo2020body2vec,
  title={body2vec: 3D Point Cloud Reconstruction for Precise Anthropometry with Handheld Devices},
  author={Trujillo-Jim{\'e}nez, Magda Alexandra and Navarro, Pablo and Pazos, Bruno and Morales, Leonardo and Ramallo, Virginia and Paschetta, Carolina and De Azevedo, Soledad and Ruderman, Anah{\'\i} and P{\'e}rez, Orlando and Delrieux, Claudio and others},
  journal={Journal of Imaging},
  volume={6},
  number={9},
  pages={94},
  year={2020},
  publisher={Multidisciplinary Digital Publishing Institute}
}
