## This is a fine-tuned version of roberta-base on the cleaned real-world dataset.
### Set up vm
- python3 -m venv venv
- source venv/bin/activate
### Install requirements
pip install -r requirements.txt
### Download data (Very large data set not recommended)
Run download_data.py. 

**you can skip the download and clean data process by using data i already uploaded https://huggingface.co/datasets/echodpp/mbti-cleaned**. 
### Clean data
Run explore.ipynb
### Train model （Highly discouraged to try and this spend more than 20 hours）
fine-tune.py 
**you can also play with the model we trained and push to hub https://huggingface.co/Shunian/mbti-classification-roberta-base-aug**
### Play with model
- watch demo_gif.mp4
- run app.py   





