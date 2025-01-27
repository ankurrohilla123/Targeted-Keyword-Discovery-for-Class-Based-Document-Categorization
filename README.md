# Class-Specific Keyword Extraction with Enhanced NLP Techniques 📝✨  

This project presents a refined approach to **keyword extraction**, specifically tailored for classifying and analyzing domain-specific documents. Built on the **KEYBERT** algorithm, it integrates advanced Natural Language Processing (NLP) techniques to extract precise and class-relevant keywords. It’s ideal for applications in document classification, topic modeling, and domain-specific text analysis.

---

## 🚀 Key Features  

- **Class-Specific Keyword Extraction**: Extracts domain-relevant keywords for precise categorization.  
- **Iterative Refinement**: Leverages **cosine similarity** to enhance keyword relevance iteratively.  
- **Scalable and Efficient**: Optimized to handle large datasets with mid-range computational resources.  
- **Multi-Algorithm Support**: Includes **TextRank**, **RAKE**, and **TF-IDF** for diverse keyword extraction.  
- **Robust Evaluation**: Demonstrated significant performance improvements over traditional methods using the **German Handelsregister** dataset.  

---

## 📂 Project Structure  

1. **Data Ingestion**: Automates data collection and preprocessing for both structured and unstructured inputs.  
2. **Keyword Extraction**: Implements enhanced keyword extraction using embedding-based scoring techniques.  
3. **Classification Module**: Categorizes documents into predefined classes using rule-based and machine-learning models.  
4. **User Interface**: Streamlit-based application for easy upload, processing, and export of analysis results.  
5. **Evaluation Metrics**: Includes metrics like **precision**, **recall**, and **F1-score** for performance assessment.  

---

## 🛠️ Installation  

1. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/your-repo-name  
   cd your-repo-name  
   ```  

2. **Create and Activate a Virtual Environment**:  
   ```bash  
   python -m venv venv  
   source venv/bin/activate  # For Windows: venv\Scripts\activate  
   ```  

3. **Install Dependencies**:  
   ```bash  
   pip install -r requirements.txt  
   ```  

---

## 📋 Usage  

1. **Run the Application**:  
   ```bash  
   streamlit run main.py  
   ```  

2. **Access the Application**:  
   Open your browser and navigate to **http://localhost:8501**.  

3. **Keyword Extraction Process**:  
   - Upload a `.docx` or `.pdf` file.  
   - Extract class-specific keywords.  
   - Export results in your preferred format (**PDF** or **Word**).  

---

## 📊 Dataset  

- **Source**: German Business Registry (**Handelsregister**).  
- **Entries**: 10,000 records classified based on the **WZ 2008 economic classification scheme**.  

---

## 📈 Results  

- **Precision@10**: 28.10% (compared to 2.38% with guided KEYBERT).  
- **Cosine Similarity**: Achieved an average match rate of **85% or higher**.  
- **Performance**: Outperformed **RAKE**, **YAKE**, and standard **KEYBERT** in class-specific keyword extraction tasks.  

---

## 🚀 Future Directions  

- **Multi-Word Keyphrase Extraction**: Extend support for extracting keyphrases of varying lengths.  
- **Multilingual Datasets**: Adapt the method for cross-lingual text analysis.  
- **Optimization**: Enhance computational efficiency of the iterative refinement process.  
- **Real-World Deployment**: Validate the approach in domains like **healthcare**, **e-commerce**, and **legal**.  

---

## 🙏 Acknowledgements  

Special thanks to **Dr. Iyappan P** and the **School of Computer Science and Engineering, VIT**, for their guidance and support throughout this project.  

---

## 📜 License  

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.  



