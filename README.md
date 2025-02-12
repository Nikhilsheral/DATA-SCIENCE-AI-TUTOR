# Data Science/AI Tutor 🎓  

This Streamlit app serves as an AI-powered tutor for Data Science students, leveraging Google's Gemini 1.5 Pro model to provide detailed explanations and examples for various Data Science topics.  

## Features  
- **Interactive Q&A:** Ask questions related to Data Science concepts, and receive in-depth, example-driven explanations.  
- **Context-Aware Responses:** The AI remains focused on Data Science queries, politely declining questions outside this domain.  
- **Mentor Support:** If the AI's explanation isn't sufficient, users are guided to connect with a mentor via a 1:1 Zoom call.  

## Technology Stack  
- **Streamlit:** For a simple and interactive user interface.  
- **Google Generative AI (Gemini 1.5 Pro):** To generate detailed and context-aware answers.  

## How It Works  
1. Enter your Data Science question in the text area.  
2. Click on "Generate ⚛️" to receive a detailed explanation with examples.  
3. If your query isn't fully resolved, a link to schedule a Zoom call with a mentor is provided.  

## Prerequisites  
- Python  
- Streamlit  
- Google Generative AI SDK (`google.generativeai`)  

## Getting Started  
1. Clone the repository:  
    ```bash
    git clone https://github.com/your-username/data-science-ai-tutor.git
    cd data-science-ai-tutor
    ```
2. Install dependencies:  
    ```bash
    pip install streamlit google-generativeai
    ```
3. Configure your Google API key in the code:  
    ```python
    ai.configure(api_key="YOUR_GOOGLE_API_KEY")
    ```
4. Run the Streamlit app:  
    ```bash
    streamlit run app.py
    ```

## Contribution  
Feel free to fork this repository, open issues, or submit pull requests to contribute to the development of this Data Science Tutor.  

## License  
This project is licensed under the MIT License.  

---

This repository aims to enhance the learning experience for Data Science enthusiasts by providing AI-powered explanations and mentor support.
