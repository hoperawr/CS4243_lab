# CS4243_lab
## Local Installation for OSX & Linux

1. Conda installation
```sh
  # Linux
  curl https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh -o miniconda.sh -J -L -k # Linux
  
  # OS X
  curl https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh -o miniconda.sh -J -L -k # OSX
  
  chmod +x miniconda.sh
  ./miniconda.sh
  source ~/.bashrc
```

2. Install python libraries
```sh
  # Clone GitHub repo
  git clone https://github.com/xbresson/CS4243_2022.git
  cd CS4243-Lab-Materials

  # Install python libraries
  conda create -n tf python=3.9
  conda activate tf
  pip install -r requirements.txt
```

3. Run the notebooks in Chrome
```sh
  jupyter notebook
```
