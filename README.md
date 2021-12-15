# CMU-15663-FinalProject
This project is highly motivated by the paper "DiffuserCam: Lensless Single-exposure 3D Imaging". 
The code I use basically follows their [implementation for 3D imaging](https://github.com/Waller-Lab/DiffuserCam) and [implementation for 2D imaging](https://github.com/Waller-Lab/DiffuserCam-Tutorial).

To build a diffuser camera, I recommend to follow the [official tutorial](https://waller-lab.github.io/DiffuserCam/tutorial.html). Once you have the hardware set up, start from the `2D_imaging` (requiring Python) to test your hardware with various scenes. To further explore 3D imaging using a diffuser camera, `3D_imaging` provides code (requiring Matlab). More detailed instructions of how to run the code is inside the `README.md` under `3D_imaging`, provided by the official implementation. Play around with the hyperparameters in `DiffuserCam_settings.m` to find the hyperparams that work best.

The data I capture can be viewed in [GoogleDrive](https://drive.google.com/drive/folders/1dNZ3ndd4am-A808H38zTpZwOZOCmqz3P?usp=sharing)