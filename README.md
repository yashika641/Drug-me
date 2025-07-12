 # 🧪 DrugSimNet – Drug Similarity Finder Using Molecular Fingerprints & NLP

**Accelerate drug discovery and repurposing** through a hybrid similarity engine that blends **molecular fingerprints** with **natural language processing** from biomedical literature.

![Banner](https://your-banner-link-or-delete-this-line)

---

## 🚀 Live Demo

🔗 [**Try the App on Streamlit**](https://your-streamlit-link)

📁 [**View this Project on GitHub**](https://github.com/yashika641/drugsimnet)

---

## 🧠 What is DrugSimNet?

**DrugSimNet** is a research-grade tool designed to help scientists, students, and bioinformaticians find **structurally and functionally similar drugs** using:
- **Molecular fingerprints** (via RDKit)
- **Drug descriptions from biomedical literature** (via BioBERT or TF-IDF)
- **Multi-modal similarity scoring**
- **Interactive UI with exportable results**

---

## 🔍 Key Features

- 🧬 **Molecular Similarity** using Tanimoto coefficient
- 📚 **Textual Similarity** via BioBERT or TF-IDF embeddings
- ⚖️ **Weighted Fusion** of structure + description similarity
- 🔍 **Top-N Similar Drug Retrieval**
- 📊 **Interactive Streamlit UI** with results visualization
- 📝 **Export reports** as CSV or PDF
- ✅ **Ready for Drug Repurposing Research**

---

## 🧰 Tech Stack

| Module                   | Tools Used                              |
|--------------------------|------------------------------------------|
| Molecular Processing     | RDKit                                    |
| NLP Embedding            | BioBERT (Hugging Face), TF-IDF (sklearn) |
| Similarity Measures      | Tanimoto Similarity, Cosine Similarity   |
| Clustering (optional)    | UMAP, DBSCAN                             |
| Frontend & UI            | Streamlit                                |
| Data Source              | DrugBank, PubChem                        |

---

## 🧪 Example Use Case

### Input: `Aspirin`

🔎 Output:
- Ibuprofen (Structural + Use Case Similarity)
- Naproxen
- Acetaminophen
- Triflusal  
…and more

💡 Use Case: **Potential alternatives or repositioning candidates**.

---

## 📦 How to Run Locally

```bash
# Step 1: Clone the repo
git clone https://github.com/yashika641/drugsimnet.git
cd drugsimnet

# Step 2: Install requirements
pip install -r requirements.txt

# Step 3: Run the Streamlit app
streamlit run app.py
````

> 🧠 You may also need to install `rdkit`, `transformers`, and `torch`.

---

## 📄 Project Structure

```
📁 drugsimnet/
├── app.py                     # Main Streamlit UI
├── utils/
│   ├── fingerprints.py        # RDKit fingerprinting
│   ├── embeddings.py          # TF-IDF / BioBERT models
│   ├── similarity.py          # Tanimoto + Cosine fusion
│   └── clustering.py          # Optional UMAP + DBSCAN
├── data/
│   ├── drugs.csv              # Drug names, SMILES, descriptions
├── outputs/                   # Exported reports
└── requirements.txt
```

---

## 📈 Future Enhancements

* ✅ Add synonym mapping + fuzzy search
* ✅ Deploy on Hugging Face Spaces or Streamlit Cloud
* 🚧 Drug–Target similarity extension (ChEMBL)
* 🚧 Interactive 2D/3D structure viewer (py3Dmol)
* 🚧 REST API support (FastAPI)

---

## 👩‍🔬 Author

**Yashika Pal**
MSc Bioinformatics | AI + Drug Discovery Enthusiast
📧 [Email Me](mailto:your.email@example.com) • 🌐 [GitHub](https://github.com/yashika641) • [LinkedIn](#)

---

## 📜 License

This project is open-source under the **MIT License**.

---

## 🤝 Contribute / Feedback

Got suggestions or want to contribute?
Open an issue or send a pull request!

[📝 Submit Feedback](https://github.com/yashika641/drugsimnet/issues)

 
 
