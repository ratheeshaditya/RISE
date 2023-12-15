# Research Institute of Sweden Assignment

**Package requirements**
The notebook is completely created & executed in Google Colab using T4 GPU, where you can directly do the pip install from the notebook itself on google colab. However, if you want to run it locally, I've uploaded the requirements.txt file for you to run it locally/cluster.

**Configuration**
- I'd recommend creating a dedicated folder for this notebook. After you mount it onto google drive, copy the path of the folder and paste it in "model_dir" variable in section 4.2 followed by /models so that the checkpoint files of System A and System B can be saved. The same applies when running it locally

**Running from checkpoint**
- If you want to run from a checkpoint, you can just pass in the path of the checkpoint folder as parameter in the trainer() function and it will resume from that point. There are comments available for you to easily follow.
