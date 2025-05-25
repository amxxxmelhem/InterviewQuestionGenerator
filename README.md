# InterviewQuestionGenerator
An interactive notebook application that uses a lightweight language model to generate customized interview questions and answers based on a job role or resume description.

---

## 📌 Features

- 🧠 **LLM-Powered Generation**: Uses `TinyLlama` for fast, local generation of interview questions and answers.
- ✍️ **Custom Input**: Enter any job title or resume summary and select the number of questions.
- 💬 **Auto Answering**: Each generated question comes with an AI-generated sample answer.
- 🧪 **Interactive UI**: Built using `ipywidgets` for seamless Jupyter Notebook interactivity.

---

## 🚀 Getting Started

### 1. Install Dependencies
```bash
pip install transformers accelerate ipywidgets
````

### 2. Run the Notebook

Open `AI_Interview_Question_Generator.ipynb` in Jupyter and execute all cells.

---

## 🧱 How It Works

1. You enter a job role or resume summary.
2. The app constructs a prompt and sends it to the TinyLlama model.
3. Questions are generated using Hugging Face's text-generation pipeline.
4. Each question is followed by a model-generated answer.

---

## 🛠️ Tech Stack

* [Transformers](https://huggingface.co/docs/transformers/index)
* [TinyLlama Model](https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0)
* [ipywidgets](https://ipywidgets.readthedocs.io/en/stable/)
* Python 3.8+

---

## 📄 Example Output

```
Q1. What is your experience with building machine learning models?

A1. I have built and deployed various ML models for classification and regression problems, using frameworks such as TensorFlow and PyTorch...
```

---

## 📂 Project Structure

```
AI_Interview_Question_Generator.ipynb  # Main interactive app
README.md                              # Project overview
pdf                                    # Detailed explaination of the code 
```


## 📜 License

This project is open-source under the MIT License.

---

## 🙋‍♀️ Author

Made with 💻 by \amxxxmelhem

```
