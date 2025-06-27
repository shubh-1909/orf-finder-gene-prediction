# 🧬 ORF Finder & Gene Prediction Tool

This mini-project scans a DNA sequence to find **Open Reading Frames (ORFs)** across all six reading frames.

It reports:
- ➕ Frame & strand (+1, +2, +3, -1, -2, -3)
- 🏁 Start & stop positions
- 📏 ORF length
- 🔍 Filters long ORFs (e.g. >100 bp)

---

## 🚀 Run on Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shubh-1909/orf-finder-gene-prediction/blob/main/ORF_Finder_Gene_Prediction.ipynb)

---

## 🔬 Features

✅ Upload a DNA FASTA file  
✅ Scans 3 forward & 3 reverse reading frames  
✅ Identifies ORFs using start (`ATG`) and stop codons (`TAA`, `TAG`, `TGA`)  
✅ Creates a summary table of ORFs  
✅ Filters for long ORFs (>100 bp)  
✅ Sorts ORFs by length to spot longest candidates for genes

---

## 🛠 Tools Used

- Python
- BioPython
- Pandas
- Google Colab

---

## 👨‍💻 Author

**Shubkarandeep Singh Judge**  
🎓 M.Sc. Biotechnology | 💻 Minor in Computer Science  
🌐 [GitHub: shubh-1909](https://github.com/shubh-1909)

---

## 📜 License

This project is licensed under the MIT License.
