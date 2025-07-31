six datasets are included: the CATMoS_LD50, Inhibitor_1368, PubChem_4504, PubChem_1336971, PubChem_449994, and New_generated_based_on_different_scaffold dataset in paper "AI-driven discovery of high-performance corrosion inhibitors using a BERT-GPT framework for molecular generation". 

## run the web service for generating and predicting, recommending corrosion inhibitors.
### Download chem_mol__assistant.zip
# 化学分子生成科研助手
1) generate new molecules and predict IE and LD50:
 <img width="831" height="329" alt="image" src="https://github.com/user-attachments/assets/53231929-678b-4fdb-8f30-47fd8ae79784" />
 <img width="841" height="353" alt="image" src="https://github.com/user-attachments/assets/0a4fb4a1-2ca0-43c5-bd47-211e62e07f5a" />
<img width="859" height="575" alt="image" src="https://github.com/user-attachments/assets/beb5b666-b849-4e90-af57-7397ae1331ea" />

2) Predict IE and LD50:
 
<img width="865" height="502" alt="image" src="https://github.com/user-attachments/assets/0e83c5ff-e455-49e0-959a-fdca10796a39" />

### 使用方法

1. 安装依赖：
```
conda create -n chem_assistant python=3.10
conda activate chem_assistant
pip install -r requirements.txt
```

2. 启动应用：
```
streamlit run app.py
```
