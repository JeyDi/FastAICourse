# FastAICourse
Repository of my FastAI Courses.

This is my Machine Learning and Deep learning journey to better understand and practise all the stuff related to Data Science with online courses.

There are different folders for any course (Machine Learning, Deep Learning and NLP).

There's also the official fast-ai repository that can be found here:

- https://github.com/fastai/fastai



Usefull links:

- FastAI official page
  - https://www.fast.ai/

- repository of ML and DL projects for experimentation (with datasets)
  - https://github.com/NirantK/awesome-project-ideas



I have worked on my machine, so there are instructions for course installation

1. Create a new conda environment

   - ```bash 
		conda create -n fastai python=3.6 anaconda 
		```
   - Go to the fast-ai folder inside the repo and launch the update command, all the  required packages will be installed (because of requirements.yaml file)
   - ```bash 
		conda env update
		```
   - ```bash 
		source activate fastai 
		```

2. If it's required Install pytorch with CUDA (based on your CUDA installation on your PC) [If you do the update with conda with the requirements.yaml file, this is not required]

   - Activate the environment and install pytorch
   
   - ```bash
     conda activate fastai
     conda install -c pytorch pytorch cudatoolkit=10.1
     ```

