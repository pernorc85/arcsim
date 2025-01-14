# ARCSim 0.3.1 Fixes and Installer Script

## 🗂 Contents
This repository is a fork of _ARCSim: Adaptive Refining and Coarsening Simulator_ 0.3.1, which you can also find [here](http://graphics.berkeley.edu/resources/ARCSim/). 
It contains bug fixes for the installation and an installer script tested on Ubuntu and Pop!\_OS 20.04 which should be compatible with other Linux distributions as well (you may need to change the repository installation from `apt-get` to your distro's one).
The script automatically detects the operating system and should also work with MacOSX - although this is untested, so any feedback will be welcome ;)


<p align="center">
  <img src="https://github.com/Juju-botu/arcsim/blob/main/flag.gif" width=600 alt="Flag simulation">
</p>

## 🛠 Setup Instructions:

Open a terminal in the folder you would like to install ARCSim and paste the following commands:

1. Clone repository:
```shell
git clone https://github.com/kaist-silab/arcsim.git && cd arcsim/
```

2. Change permissions and install:
```shell
sudo chmod +x install.sh && sudo ./install.sh
```

## 📬 Feedback
If you find any problems, feel free to raise an `Issue` or to contribute with a `Pull Request`!


## 📜 Credits

I am not the author of this code, I just made modifications to the code and created the `install.sh` script. Full credits go to the original authors. If you use this code for a publication, make sure to cite the following papers:

>Rahul Narain, Armin Samii, and James F. O'Brien. "Adaptive Anisotropic Remeshing for Cloth Simulation". ACM Transactions on Graphics, 31(6):147:1–10, November 2012. Proceedings of ACM SIGGRAPH Asia 2012, Singapore.

>Rahul Narain, Tobias Pfaff, and James F. O'Brien. "Folding and Crumpling Adaptive Sheets". ACM Transactions on Graphics, 32(4):51:1–8, July 2013. Proceedings of ACM SIGGRAPH 2013, Anaheim.

>Tobias Pfaff, Rahul Narain, Juan Miguel de Joya, and James F. O'Brien. "Adaptive Tearing and Cracking of Thin Sheets". ACM Transactions on Graphics, 33(4):110:1–9, July 2014. Proceedings of ACM SIGGRAPH 2014, Vancouver.

Special thanks go to @DanielTakeshi for [his instructions](https://github.com/DanielTakeshi/ARCSim-Installation-Instructions)!

