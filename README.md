# Pepeline Development AI in Ubuntu 18.04. 

# Overview my Specifications computer. 
OS: Ubuntu 18.04 LTS Version. 
GPU: TITAN RTX 2080 TI. 
RAM: 128 GB RAM.
CPU: i9900K Unlocked. 

### steps: 
1. Install Ubuntu 18.04 LTS error on my computer no see screen. 
Solution: Mode Booting - Recovery Mode and Enable Network and Click Resume. 

2. Install Driver Titan RTX 2080 TI - Open Software & Updates NVIDIA Driver metapackage from nvidia-driver-430 or later. (proprietary, tested)

3. Install Cuda 10.0: 
https://developer.nvidia.com/cuda-10.0-download-archive?target_os=Linux&target_arch=x86_64&target_distro=Ubuntu&target_version=1804&target_type=deblocal

1. `sudo dpkg -i cuda-repo-ubuntu1804-10-0-local-10.0.130-410.48_1.0-1_amd64.deb`
2. `sudo apt-key add /var/cuda-repo-<version>/7fa2af80.pub`
3. `sudo apt-get update`
4. `sudo apt-get install cuda`
ERROR: 
The following packages have unmet dependencies:
 cuda : Depends: cuda-10-0 (>= 10.0.130) but it is not going to be installed
E: Unable to correct problems, you have held broken packages.

### Solution: 
5. 'sudo add-apt-repository universe'
6. 'sudo apt-get update'
7. 'sudo apt-get install freeglut3 freeglut3-dev libxi-dev libxmu-dev'



### other command: 
ssh-keygen -p -f id_ssh_file


