# VisBias
This repo contains the code and results for **VisBias**.  
You’ll find four tasks implemented in [code/api_call.ipynb](code/api_call.ipynb), and the corresponding results are stored under `./results`.


## 📂 Project Structure
- `./source` → All source images  
- `./results` → Processed results for each task  
- `./code` → Implementation and evaluation scripts 

## 🚀 How to Run

### 1. 🔑 Call API
To get started with different models:  

1. Run the **first code block** in [code/api_call.ipynb](code/api_call.ipynb) to install all required libraries.  
2. Scroll down to the section for the model you want to use — you’ll see **four different API calling methods**.  
3. Replace the placeholder with your own `api_key`.  
4. *(Optional)* Add export code if you want to save results to your local machine.  


### 2. 🧹 Data Cleaning
Before evaluation, you need to clean the raw outputs:  

- For the **form completion task**, run [code/Result_Cleaning_for_Form.ipynb](code/Result_Cleaning_for_Form.ipynb) to generate data in the correct format for evaluation.  


### 3. 📊 Evaluation

For the **image description task**, we provide multiple evaluation methods:  

1. Run [code/image_description/sentiment.ipynb](code/image_description/sentiment.ipynb) → Sentiment analysis  
2. Run [code/image_description/marked_words.py](code/image_description/marked_words.py) → Extract marked words

In addition, we also provide scripts for generating tables and figures used in the paper:  

1. Run [code/image_description/table.ipynb](code/image_description/table.ipynb) → Generate tables for the paper  
2. Run [code/figure_generation.ipynb](code/figure_generation.ipynb) → Generate paper figures, compute JSD scores, and visualize them  

---
