# distance_differences_ives
This repository contains the Unity project of the paper with the title "Development and evaluation of a test setup to investigate distance differences in immersive virtual environments" published at QoMEX 2020.

It is designed to investigate shifts between a real object and the virtual replication of that object in immersive virtual environments (IVE) of the same size.

## Download Unity3D package
Please download the required Unity3D package here: [https://doi.org/10.5281/zenodo.4090934](https://doi.org/10.5281/zenodo.4090934)

## Requirements
This project is designed for Unity version 2019.2.0f1 using Windows 10.
It also has been tested with Unity version 2019.3.11f1 using Windows 10.
Other Unity versions have not been tested.
This project was developed for the HTC Vive Pro Head-Mounted Display and a HTC Vive Tracker (2018).

## Configuration
To run this project, a HTC Vive Tracker, HTC Vive Controllers and a HTC Vive Pro are needed.

If you want to make exactly the same objects used in the paper's study, please find the dimensions here:
* Open cylinder (fixed on the table): 10.1 cm diameter, 3.8 cm height
* Closed cylinder (interactable object): 8.4 cm diameter, 11.7 cm height

To get the project running, create a new project and import the `distance_differences_ives.unitypackage` in Unity (Assets >> Import Package).

## Acknowledgements
If you use any or parts of the Unity project or parts of it, please cite the following paper or include a link to this repository.

```
@inproceedings{fremerey2020development,
	title={Development and evaluation of a test setup to investigate distance differences in immersive virtual environments},
	author={Fremerey, Stephan and Suleman, Muhammad Sami and Azeem Paracha, Abdul Haq and Raake, Alexander},
	booktitle={Twelfth International Conference on Quality of Multimedia Experience (QoMEX)},
	year={2020},
	organization={IEEE}
}
```
