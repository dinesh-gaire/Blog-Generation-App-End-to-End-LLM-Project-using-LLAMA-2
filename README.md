# Blog-Generation-App-End-to-End-LLM-Project-using-LLAMA-2
## 📝 Project Overview
This is an end-to-end Blog Generation application powered by LLAMA-2, a large language model that can generate blog content based on user-specified topics, writing styles, and word count.
## ✨ Features

* **Flexible Blog Generation:** Create blogs for different professional profiles
* **Customizable Length:** Control the number of words in your blog
* **Multiple Writing Styles:** Choose from various professional perspectives
* **User-Friendly Interface:** Simple Streamlit-based application

## 🛠 Prerequisites

* Python 3.8+
* LLAMA-2 model (7B Chat version)

## 🚀 Installation
##### 1. Clone the Repository
```
git clone https://github.com/dinesh-gaire/Blog-Generation-App-End-to-End-LLM-Project-using-LLAMA-2.git
cd Blog-Generation-App-End-to-End-LLM-Project-using-LLAMA-2
```
##### 2. Create a Virtual Environment
```
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```
##### 3. Install Dependencies
```
pip install -r requirements.txt
```
##### 4. Download LLAMA-2 Model

* Download the LLAMA-2 7B Chat model (GGML version)
* Place the model file in the `models/` directory
* Ensure the model filename matches `llama-2-7b-chat.ggmlv3.q8_0.bin`

## 🖥 Running the Application
```
streamlit run app.py
```
## 📘 How to Use
1. Enter a blog topic
2. Specify the number of words
3. Select a writing style (Researchers, Data Scientist, Common People)
4. Click "Generate" to create your blog

## ⚙ Model Configuration

* **Model:** LLAMA-2 7B Chat
* **Max New Tokens:** 256
* **Temperature:** 0.01

## 🧰 Technologies Used

* Streamlit
* LangChain
* CTransformers
* LLAMA-2

## 🔧 Customization
You can modify the following in `app.py`:

* Add more writing styles
* Adjust model parameters
* Change prompt template

## 🐛 Troubleshooting

* Ensure LLAMA-2 model is correctly downloaded and placed in the `models/` directory
* Check Python and dependency versions
* Verify GPU compatibility for faster inference (optional)

## 🙏 Acknowledgments

* LLAMA-2 Model by Meta AI
* LangChain Community
* Streamlit

## 🤝 Contributions
Contributions, issues, and feature requests are welcome!
##### How to Contribute

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
