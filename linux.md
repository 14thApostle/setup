## Setup Linux Environment

Since we are on linux, we already have a script file which you can run to install all the necessary packages.

The script file included is a mini version of https://github.com/rsnk96/Ubuntu-Setup-Scripts . If you want a proper setup ubuntu, do follow the original repo.

To have a minimal setup with all the necessary stuff

 1) chmod +x setup_linux.sh
 2) ./setup_linux.sh

The script will ask whether you want VS Code, Atom or Sublime. Feel free to q and install any other one of your choice.

The setup_linux.sh will will setup your terminal, anaconda, a code editor, bash aliases and a few more packages. 
#### Do a restart after the script before continuing.

And run (for non-gpu tensorflow)
``` 
$ pip install tensorflow
```
As just installing tensorflow wont let you use the gpu, you need to install CUDA(for Nvidia) and tensorflow-gpu for using the gpu.
Refer https://www.tensorflow.org/install/gpu for more about this.

#### Use [colab](https://colab.research.google.com/) for now if you really need a GPU as you can get a GPU instance for free.

Refer https://pytorch.org/ on how to install pytorch.

### Feel free to open an issue on this repo or PM any one of the club members if you face any issues.

