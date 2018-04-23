# Data-Open-Lecture

Lecture repository: Introduction to Data Analysis with R and Python

## Preparation

### For Python

1. Clone lecture repository with shell command `git clone https://github.com/founderfan/Data-Open-Lecture`
2. Download and install [Anaconda](https://www.continuum.io/downloads) (Python 3 version)
3. After installation, run command in a new shell: `jupyter lab`
4. If you run jupyter lab in a linux server through ssh, open a new terminal
    - Connect remote jupyter port wit local port: `ssh -L 8000:localhost:(jupyter port, default is 8888) (user)@(server address)`
    - after log in, `jupyter notebook list`, check and copy the token of your jupyter
    - open browser http://localhost:8000/, enter the token
5. Create a new notebook: Left-upper area -> "+" (New launcher) -> Notebook -> Python 3
6. Be ready to type in code!

### For R

1. Download and Install [R](https://cloud.r-project.org/) *and* [R-studio](https://www.rstudio.com/products/rstudio/download/)
2. Open Rstudio
3. Create a new R script: Left-upper area -> File -> New File -> R script
4. Download the lecture notes "RLecture.html" and dataset "Diamonds.csv" from [lecture repository](https://github.com/founderfan/Data-Open-Lecture)
5. Be ready to type in code!
