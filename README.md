# IBM-Call-For-Code-2024

## A Personal Finance Generative AI Assistant using IBM-Granite-7B-Instruct

---

### Introduction

In today's rapidly changing financial landscape, effective personal finance management is crucial. **Wealth Wiser**, our innovative generative AI assistant, leverages the power of IBM's Granite-7B-Instruct model to provide users with personalized financial advice and insights. By employing QLoRA for fine-tuning and utilizing Gradio for an interactive user interface, we aim to empower individuals to navigate their financial journeys with confidence and clarity.

### Features

- **Personalized Financial Insights**: Wealth Wiser analyzes user inputs such as income, expenses, and savings goals to offer tailored investment strategies.
- **Real-Time Recommendations**: Access up-to-date suggestions for Systematic Investment Plans (SIPs) and promising stocks based on current market trends.
- **Dynamic Market Analysis**: Utilizing sentiment analysis and named entity recognition to continuously adapt advice according to market conditions.
- **User-Friendly Interface**: Built with Gradio, the interface allows easy interaction for users of all financial backgrounds.

### Technology Stack

- **Model**: IBM-Granite-7B-Instruct
- **Fine-Tuning Framework**: QLoRA
- **User Interface**: Gradio
- **Data Management**: ChromaDB, VectorDB for efficient storage and retrieval of financial data.

### Collaborators

- **MeiyazhaganBK**
- **Shashmithayoganarajah**
- **YeswanthNarayanan**

### Technologies Used

- torch	
- transformers	
- accelerate	
- bitsandbytes	
- peft	
- trl	
- gradio	
- bs4	
- uuid	
- chromadb

### Getting Started

To run Wealth Wiser locally:

1. Clone the repository:
   ```bash
   git clone (https://github.com/AKILSADIK/IBM-Call-For-Code-2024).git
   cd IBM-Call-For-Code-2024
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python app.py
   ```

### Usage

Once the application is running, simply enter your financial details into the user interface. Wealth Wiser will analyze the inputs and provide personalized recommendations to help you achieve your financial goals.

### Contribution

We welcome contributions to improve Wealth Wiser! If you have suggestions or find any issues, please feel free to submit a pull request or open an issue in the repository.

### License

This project is licensed under the MIT License.

---

Empower your financial decisions with Wealth Wiser—your AI-powered personal finance assistant!
