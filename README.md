Running-Llama2-on-CPU-Machine
How to run?
STEPS:
## Clone the repository

Project repo: `https://github.com/sumityadav329/Llama2-on-CPU-Machine.git`
## STEP 01- Create a conda environment after opening the repository
``` bash
conda create -n llmapp python=3.8 -y
conda activate llmapp
```
## STEP 02- install the requirements
``` bash
pip install -r requirements.txt
python app.py
```
Download the quantize model from the link provided in model folder & keep the model in the model directory:
## Download the Llama 2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin


## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main