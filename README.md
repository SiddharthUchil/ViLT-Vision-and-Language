# Visual-ChatGPT 🤗💬👁️

ViLT-GPT is an innovative application that gives the conversational AI ChatGPT the ability to "see". By integrating OpenAI's Language Models (LLM) and LangChain with Vision-and-Language models, this app can answer queries based on the content of images. Now, you can interact with your images, ask questions and get informative responses.

![vilt](https://github.com/SiddharthUchil/ViLT-Vision-and-Language/assets/36127139/e9abca5b-fdd0-48a3-9ea6-dd1b40c1d25e)


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before running the app, make sure you have the following libraries installed:

- dotenv
- os
- streamlit
- PIL
- transformers
- LangChain
- Streamlit Extras

## How to use

To use this app, follow these steps:

1. Launch the app.
2. In the sidebar, click on 'Upload your IMAGE' to upload an image.
3. Ask a question related to the uploaded image in the text input field.
4. Wait for the processing to finish, and the answer to your question will appear below.
5. Click 'Cancel' to stop the process.

## Built With

- [Streamlit](https://streamlit.io/) - The web framework used
- [LangChain](https://python.langchain.com/) - The language modeling framework
- [OpenAI](https://platform.openai.com/docs/models) - The language understanding model
- [ViLT](https://huggingface.co/dandelin/vilt-b32-finetuned-vqa) - Vision-and-Language model from Hugging Face

## Authors

- [Siddharth Uchil](https://twitter.com/siddharthuchil)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
