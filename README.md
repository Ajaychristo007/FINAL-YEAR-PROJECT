# AI Exam Controller

## 📌 Overview
AI Exam Controller is an intelligent examination management system designed to automate the complete examination lifecycle, including question paper generation, answer sheet evaluation, marks processing, and secure result publication. The system integrates Artificial Intelligence, Natural Language Processing (NLP), OCR, and Blockchain technology to improve accuracy, transparency, efficiency, and security in examination systems. :contentReference[oaicite:0]{index=0}

---

## 🎯 Objectives
- Automate question paper generation from subject PDFs
- Evaluate descriptive answers using AI-based semantic analysis
- Reduce manual effort and evaluation time
- Ensure fair and consistent marking
- Prevent result tampering using blockchain technology
- Improve transparency and scalability in examination management

---

## 🚀 Features
- 📄 AI-generated question papers
- 🧠 Semantic answer evaluation using BERT
- 🔍 OCR-based answer sheet text extraction
- 🔐 Blockchain-based secure marks storage
- 📊 Automated marks calculation
- 👨‍🏫 COE verification dashboard
- 📢 Result publishing and notification system
- 👥 Role-based access management

---

## 🛠️ Technologies Used

### Backend
- Python
- Flask

### Frontend
- HTML
- CSS
- Bootstrap

### Database
- MySQL

### AI & NLP
- T5 Transformer
- BERT
- TF-IDF
- TextRank
- Cosine Similarity

### OCR & Image Processing
- OpenCV
- Tesseract OCR

### Blockchain
- SHA-256 Hashing
- JSON-based Blockchain Ledger

---

## ⚙️ System Workflow

### 1. Subject PDF Upload
Faculty uploads syllabus or subject PDFs into the system.

### 2. Content Extraction
PyMuPDF extracts and cleans text content from uploaded PDFs.

### 3. Concept Identification
TF-IDF and TextRank algorithms identify important concepts and keywords.

### 4. Question Generation
The T5 Transformer model generates meaningful examination questions automatically.

### 5. Answer Sheet Upload
Invigilators upload scanned answer sheets after examination.

### 6. OCR Processing
Tesseract OCR extracts machine-readable text from answer sheets.

### 7. Semantic Evaluation
BERT embeddings and cosine similarity are used to compare student answers with reference answers.

### 8. Marks Calculation
Marks are automatically assigned based on similarity scores.

### 9. Secure Blockchain Storage
Final marks are securely stored using blockchain hashing mechanisms.

### 10. Result Publication
The Controller of Examinations verifies and publishes results securely. :contentReference[oaicite:1]{index=1}

---

## 📊 Modules
- System Administrator
- Faculty / Examiner
- Examination Invigilator
- Controller of Examinations (COE)
- Student Management
- Subject Content Analysis
- Question Paper Generation
- Answer Sheet Evaluation
- Marks Management
- Result Publishing
- Notification System
- Reports & Analytics

---

## 📈 Advantages
- Reduces manual workload
- Faster evaluation and result processing
- Accurate and unbiased evaluation
- Secure and tamper-proof marks storage
- Scalable for universities and institutions
- Enhances transparency in examinations

---

## 🧠 Algorithms Used

| Function | Algorithm |
|----------|------------|
| PDF Processing | PyMuPDF |
| Concept Extraction | TF-IDF, TextRank |
| Question Generation | T5 Transformer |
| OCR | Tesseract OCR |
| Semantic Understanding | BERT |
| Similarity Calculation | Cosine Similarity |
| Blockchain Security | SHA-256 Hashing |

---

## 🔒 Security Features
- Role-based authentication
- Secure session handling
- Blockchain tamper detection
- SQL injection prevention
- Protected result verification workflow

---

## 📂 Dataset
The system uses educational NLP datasets such as:
- Stanford Question Answering Dataset (SQuAD)

These datasets help train and evaluate NLP models for question generation and semantic answer evaluation. :contentReference[oaicite:2]{index=2}

---

## 🧪 Testing
The project includes:
- Unit Testing
- Integration Testing
- Performance Testing
- Security Testing

All major modules were tested successfully for functionality, security, and scalability.

---

## 🌍 Future Enhancements
- Online examination support
- Multilingual answer evaluation
- AI proctoring integration
- Cloud deployment
- Explainable AI (XAI) evaluation reports
- Advanced analytics dashboard

---

## 👨‍💻 Authors
- Ajay Christo P
- Dharanidharan S
- Koteeswarar MM
- Shahanas M
