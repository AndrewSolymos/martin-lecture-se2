# SE2 Lecture 'GrammarBasedFuzzing' README

# For the Summer semester 2026 questions can be asked at: andrewsolymos@gmail.com

## Install guide:
- Info for conda on Windows:
  https://docs.conda.io/projects/conda/en/stable/user-guide/install/windows.html

- Install after Conda on Windows
  - Run Anaconda promt
  - Create virtual env (THIS IS mandatory)
  ```
  conda create -n fuzzenv python=3.11 -y
  conda activate fuzzenv
  ```
  
  -Install packages (should not give any error now)
  ```
  pip install graphviz
  pip install jupyter
  pip install fuzzingbook numpy alhazen-py
  ```
  - Run Jupyter
  ```
  jupyter-notebook
  ```
  
- On Linux:
  https://docs.conda.io/projects/conda/en/stable/user-guide/install/linux.html

- Insall Conda On Linux
  Navige with Terminal to a Folder of your choice and run these commands line-by-line: 
  ```
  $ wget wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
  $ bash Miniconda3-latest-Linux-x86_64.sh

  $ conda activate
  ```
- Create new Environment, switch and install
  ```
  conda create --name fuzzingHomeWork python=3.10
  conda activate fuzzingHomeWork
  pip install graphviz
  pip install jupyter
  pip install fuzzingbook numpy alhazen-py 
  ```

- If errors emerge run:
  ```
  sudo apt-get update
  sudo apt-get install graphviz libgraphviz-dev pkg-config
  pip install fuzzingbook numpy alhazen-py 
  ```

- Run Jupyter
  ```
  jupyter-notebook
  ```

## Original: Getting started

- Download [Python 3.10](https://www.python.org/downloads/) (You will need at least >= Python 3.10)
   
  Some variation of
  ```
  $ sudo apt-get install python3.10
  ```
- Install [Graphviz](https://graphviz.org/download/) for your operating system.
  
  Some variation of
  ```
  $ sudo apt install graphviz
  ```
- Make a virtual environment (recommended)
  ```
  $ python3 -m venv venv
  $ source venv/bin/activate
  ```
- Verify virtual environment
  ```
  $ which python3
  ```
  This should point to the just created location.

- Install [Jupyter](https://jupyter.org/).
  ```
  $ python3 -m pip install jupyter
  ```
- Install dependencies.
  ```
  $ python3 -m pip install fuzzingbook numpy alhazen-py 
  ```
- Start the Jupyter server in the repository directory
  ```
  $ jupyter-notebook
  ```
  This opens a browser window at http://localhost:8888/tree

### Start:

- Navigate the directory, and start the jupyter-notebook `GrammarBasedFuzzing.ipynb`.


### Package Requirements:

- pandas, numpy, ipynb
- fuzzingbook
- jupyter-notebook
- sci-kit learn
- graphviz

### Maintainer

- Martin Eberlein (martin.eberlein@hu-berlin.de)
