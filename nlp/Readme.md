## This is a fine-tuned version of roberta-base on the cleaned real-world dataset.
### set up vm
- python3 -m venv venv
- source venv/bin/activate
### install requirements
pip install -r requirements.txt
### Download data
Run download_data.py
### Clean data
Run explore.ipynb
### Train model
fine-tune.py
### Play with model
- watch demo_gif.mp4
- run app.py 

