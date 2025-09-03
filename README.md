# 🤝 Friend Recommendation using Graph Neural Network (GNN)

A simple **Graph Neural Network (GNN)** project that recommends new friendships in a small social network.  
Built using **PyTorch Geometric** in **Google Colab** or **Locally (Python 3.9+)**.  

---

## 🌟 Project Idea
- Each **person = Node**  
- Each **friendship = Edge**  
- GNN learns embeddings for people  
- Link prediction suggests possible new friendships  




---

## 📂 Project Structure

- 📜 **friend_recommendation.ipynb** → Notebook (Colab version)  
- 📜 **friend_recommendation.py** → Python script  
- 📜 **requirements.txt** → Dependencies  
- 📜 **README.md** → Documentation
---
## 🔧 Installation & Running

### ▶️ Run on Google Colab (Recommended)
1. Open [Google Colab](https://colab.research.google.com)  
2. Create a new notebook  
3. Install dependencies:  

```bash
!pip install torch torchvision torchaudio
!pip install torch-scatter torch-sparse torch-cluster torch-spline-conv torch-geometric -q
```
---

### 💻 Run Locally (Python 3.9+)


#### 1️⃣ Clone repo
```bash
git clone https://github.com/your-username/friend-recommendation-gnn.git
cd friend-recommendation-gnn
```
#### 2️⃣ Create virtual environment
```bash
python -m venv venv
```
### Activate environment:
  #### Windows:
  ```bash
  venv\Scripts\activate
```
#### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

#### 4️⃣ Run script
```bash
python friend_recommendation.py
```










