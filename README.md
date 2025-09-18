# cebmf_seqRNA
This repository contains initial developments for using cebmf methods on RNA sequences

Use the debmf_dataset_generation.ipynb notebook. If raw data is on disk, install Java JDK in Ubuntu:

```bash
sudo apt-get update
sudo apt-get install default-jdk
```

Create a Python virtual environment:

```bash
python3 -m venv venv
```

Activate the virtual environment:

```bash
source venv/bin/activate
```

Install relevant python packages:

```bash
pip install -r requirements.txt
```

Then run debmf_dataset_generation.ipynb from start to end. 

