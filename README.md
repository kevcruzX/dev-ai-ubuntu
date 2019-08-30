# Pepeline Development AI in Ubuntu 18.04. 

# Overview my specifications computer. 
OS: Ubuntu 18.04 LTS Version. 
GPU: TITAN RTX 2080 TI. 
RAM: 128 GB RAM.
CPU: i9900K Unlocked. 

### Workaround BlackScreen Ubuntu 18.04.
1. workaround affter Install Ubuntu 18.04 
Enter:  Recovery Mode and `Enable Network`, affter Continue Select `Resume`. 

### Recommended Install GCC Compiler 

1. Start by updating the packages list: 

`sudo apt update`

2. Install the build-essential package by typing:

`sudo apt install build-essential`
 
The command will instlal a bunch of new packages including gcc, g++ and make.

You may also want to install the manual pages about using GNU/Linux for development:

`sudo apt-get install manpages-dev`

To Validate that the GCC compiler is successfully installed use the gcc --verison command which will print the GCC version:

`gcc --version`


### Tutorial For Install Drivers Nvidia RTX 2080 Ti, for Ubuntu 18.04 Final Solution

[Install Drivers  RTX2080TI and Cuda 10.0](https://medium.com/better-programming/how-to-install-nvidia-drivers-and-cuda-10-0-for-rtx-2080-ti-gpu-on-ubuntu-16-04-18-04-ce32e4edf1c0)

  


### other command: 
ssh-keygen -p -f id_rsa / change password a private key.
chmod 400 id_rsa / Permission for use key add.

