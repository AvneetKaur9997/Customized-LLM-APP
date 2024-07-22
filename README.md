# Indian Classical Dance Explorer

This is a Gradio-based chatbot that helps users explore various Indian classical dance forms such as Bharatanatyam, Kathak, Kathakali, Kuchipudi, Manipuri, Mohiniyattam, Odissi, and Sattriya. The chatbot uses the HuggingFace Zephyr-7b-beta model and Retrieval-Augmented Generation (RAG) to provide accurate and informative responses about these dance styles.

## Features

- Explore different Indian classical dance forms
- Learn about Bharatanatyam, Kathak, Kathakali, Kuchipudi, Manipuri, Mohiniyattam, Odissi, and Sattriya
- Interactive chat interface built with Gradio
- RAG-based system to provide contextually relevant information
- Customizable system messages, token limits, temperature, and top-p values

## Requirements

- Python 3.x
- `gradio`
- `huggingface_hub==0.22.2`
- `PyMuPDF`
- `sentence-transformers`
- `numpy`
- `faiss-cpu`

You can install the required packages using the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/indian-classical-dance-explorer.git
cd indian-classical-dance-explorer
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Add your PDF file (e.g., `indian_classical_dances.pdf`) to the project directory.

4. Run the application:

```bash
python app.py
```

The application will launch a Gradio interface in your browser, where you can interact with the chatbot.

## File Structure

- `app.py`: The main application script containing the Gradio interface, chatbot logic, and RAG implementation.
- `requirements.txt`: The file listing the required Python packages.
- `indian_classical_dances.pdf`: The PDF file containing information about Indian classical dances (you need to add this file).

## Customization

You can customize the system message, max tokens, temperature, and top-p values through the Gradio interface. Additionally, you can add more examples to guide the interaction with the chatbot.

## Example Questions

- What are the main Indian classical dance forms?
- Can you explain the origins of Bharatanatyam?
- How does Kathak differ from other classical dance forms?
- What are the distinctive features of Kathakali?
- Tell me about the costume and makeup in Kuchipudi.
- What is unique about Manipuri dance?
- How is Mohiniyattam different from other South Indian dance forms?
- What are the key elements of Odissi dance?

## Acknowledgments

- [Gradio](https://www.gradio.app/) for the easy-to-use interface
- [HuggingFace](https://huggingface.co/) for the powerful language model
- [PyMuPDF](https://pymupdf.readthedocs.io/en/latest/) for PDF processing
- [SentenceTransformers](https://www.sbert.net/) for embedding models
- [FAISS](https://faiss.ai/) for the vector database

For more information on `huggingface_hub` Inference API support, please check the [docs](https://huggingface.co/docs/huggingface_hub/v0.22.2/en/guides/inference).

---

