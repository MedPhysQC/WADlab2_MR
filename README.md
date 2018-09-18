# WADlab2_MR
Matlab based MRI analysis module for WADQC2 software
See [Wiki](../../wiki) for documentation.

This was compiled with Matlab 2018a for Linux and depends on installation of the Matlab runtime engine.

# DOWNLOAD and INSTALL MCR
Download and install the Matlab Runtime engine (MCR) version 2018a / MCR 9.4 with:

```
mkdir MCR_install
cd MCR_install
wget http://ssd.mathworks.com/supportfiles/downloads/R2018a/deployment_files/R2018a/installers/glnxa64/MCR_R2018a_glnxa64_installer.zip
unzip MCR_R2018a_glnxa64_installer.zip
# for scripted installation
./install -mode silent -agreeToLicense yes -destinationFolder $HOME/MATLAB_Runtime
# or for interactive installation simply use
# ./install
```

Recommended install location for the runtime engine (MCR) is $HOME/MATLAB_Runtime (e.g. /home/wad/MATLAB_Runtime)
Install as WAD user.

Also supported is the default location /usr/local/MATLAB/MATLAB_Runtime
In this case install MCR requires root previleges.

If the above download address isn't working locate it here:
http://www.mathworks.com/products/compiler/mcr/index.html
