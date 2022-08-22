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
  git clone https://github.com/Jingming517/CS4243_lab.git
  cd CS4243_lab

  # Install python libraries
  conda create -n tf python=3.9
  conda activate tf
  pip install -r requirements.txt
```

3. Run the notebooks in Chrome
```sh
  jupyter notebook
```

## Local Installation for Windows
1. Install Anaconda
```sh
https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe
```

2. Open an Anaconda Terminal   
Go to Application => Anaconda3 => Anaconda Prompt 

3. Install git : Type in terminal
```sh
  conda install git 
  git clone https://github.com/Jingming517/CS4243_lab.git
  cd CS4243_lab
```

4. Create Conda environment
```sh
 conda create -n tf python=3.9
 conda activate tf
 ### Install TensorFlow
 pip install -r requirements.txt
```
5. Run the notebooks in Chrome
```sh
  jupyter notebook
```


