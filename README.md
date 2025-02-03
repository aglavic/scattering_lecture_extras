# Neutron Scattering Lecture
Ressources to be used with the UZH scattering course
https://www.physik.uzh.ch/en/teaching/PHY585/FS2025.html

# Installation
Install python on your local machine and create a virtual environment. On Windows I'd recommand [anaconda](https://www.anaconda.com/download/success) and run in the anaconda prompt:

```
conda create -n nsc25 python=3.12
conda activate nsc25
conda install git

git clone https://github.com/aglavic/scattering_lecture_extras.git nsc25
cd nsc25
pip install -r requirements.txt
```

# Execute Jupyter Notebooks
```
jupyter notebook
```
This should open a browser with the jupyter notebooks within the repository.
