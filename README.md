

# 🧠 Generative Text Model (LSTM-Based AI Text Generator)


A lightweight AI Text Generation project using **LSTM and Flask** that generates coherent, readable paragraphs across multiple domains including **Healthcare, Finance, and Education**. The system is domain-aware, memory-efficient, and optimized for low-resource machines.


## 📌 Project Overview

The AI Text Generator takes a user-provided topic or seed text as input and produces a coherent paragraph based on domain-specific datasets. It uses a custom-trained **LSTM (Long Short-Term Memory)** model for text generation and a **Flask** web interface for user interaction.


## 🎯 Key Goals

* Multi-domain text generation
* Readable and meaningful outputs
* Domain detection for better relevance
* Lightweight and efficient model
* Professional single-page web interface


## ✨ Features

* Domain-aware text generation
* Supports Healthcare, Finance, and Education topics
* Generates coherent paragraphs
* Simple and clean UI using Flask
* Runs on low-resource machines


## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* LSTM (Deep Learning)
* Flask
* NumPy
* HTML, CSS


## 🔄 Workflow

1. User enters a topic or seed text in the web interface.
2. System detects domain based on keywords.
3. LSTM model generates word sequences.
4. Templates ensure grammar and readability.
5. Generated paragraph is displayed on the same page.

<p >
  <img src="https://private-user-images.githubusercontent.com/207546110/531457852-51456104-07a3-44cf-8b1b-fcaa29fb7b91.jpeg?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzEwNjc3NDAsIm5iZiI6MTc3MTA2NzQ0MCwicGF0aCI6Ii8yMDc1NDYxMTAvNTMxNDU3ODUyLTUxNDU2MTA0LTA3YTMtNDRjZi04YjFiLWZjYWEyOWZiN2I5MS5qcGVnP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI2MDIxNCUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNjAyMTRUMTExMDQwWiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9YzJlYzUxY2IwMTVmNGJmYWJjOTIzOWRhMjlmNzNlMTQ3Mzg0MTkwZjljZWM3ZWIwNDRkYTAyOTcwZjIwNWY3NyZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QifQ.kCO2fOZKsWvoOzFnUNfw9akrM7Zz6A-DZHHU5hjQb60" width="500"/>
</p>

## 📂 Project Structure
```
Generative-Text-Model/
│
├── dataset/
│   ├── healthcare.txt
│   ├── finance.txt
│   └── education.txt
│
├── model/
│   └── text_generator.h5
│
├── static/
│   └── style.css
│
├── templates/
│   └── index.html
│
├── app.py
├── requirements.txt
└── README.md
```



# ⚙️ Installation

# 1. Clone the Repository

```
git clone https://github.com/yourname/Generative-Text-Model.git
cd Generative-Text-Model
```



# 2. Create Virtual Environment (Optional but Recommended)

```
python -m venv venv
venv\Scripts\activate      (Windows)
source venv/bin/activate   (Linux/Mac)
```


# 3. Install Dependencies

```
pip install -r requirements.txt
```


# ▶️ How to Run the Project

```
python app.py
```

After running, open your browser and go to:

```
http://127.0.0.1:5000/
```



# 📤 Output

* User enters a topic
* AI generates a domain-specific paragraph
* Output is displayed instantly on the webpage



# 📈 Future Enhancements

* Add more domains (Sports, Technology, News, Entertainment)
* Improve model accuracy using Transformer models
* Add user authentication
* Deploy application on cloud



