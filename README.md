# Challenge 1: Customer Footfall Count</p>

<h1><p align="center">Person Counting/Tracking using YOLOv5 + DeepSORT + PyTorch</p>
<p align="center">:princess: :man: :cop: :girl: :boy:</p>
</h1>
<p align="center">A project for counting people using <code>YOLOv5</code> for model training, <code>DeepSORT</code> for tracking, <code>PyTorch</code> as the model framework </p>
<p align="center"><img src="results/result.gif"/></p>


## Objective
By the end of the challenge, your machine learning model should:
1. Be able to give a cumulative sum of the number ofpeoplein and out of the place.
2. Have bounding boxes around a detected person.
3. Have a near real time inference speed.

## Model
Download the weight model [here](https://drive.google.com/file/d/1f7zMADBvtre6t3QzLCxcZ9jxN7KUvw1b/view?usp=sharing)
### 1. Setup Environment
```bash
# Create environment 
python -m venv myvenv

# Activate the environment
myvenv\Scripts\activate

# Install all the packages 
pip install -r requirements.txt

```

