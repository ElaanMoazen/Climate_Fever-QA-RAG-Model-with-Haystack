# Climate_Fever-QA-RAG-Model-with-Haystack
### Transfer Learning with RAG Models

## Project Objective
The objective of this project is to experiment with a QA RAG (Retrieval-Augmented Generation) model on the climate_fever dataset using the Haystack framework. The goal is to go through the entire process of fitting the parts of an RAG model together and learn how to prompt it with queries to get answers from the provided dataset.

## Prerequisites
- Python 3.7 or above
- Jupyter Notebook or JupyterLab
- A compatible runtime environment (TPU or GPU recommended for faster training)

## Installation
First, clone the repository:
```bash
git clone https://github.com/yourusername/climate_fever_qa_rag.git
cd climate_fever_qa_rag
```

# Experimenting with QA RAG Model on Climate Fever Dataset

## Project Structure

The project is structured as follows:

1. **Dataset Preparation**:
   - Load the climate_fever dataset.
   - Extract and format the necessary information from the dataset.

2. **Document Storage**:
   - Set up a document store to store the formatted documents from the dataset.
   - Use the BM25Retriever to retrieve relevant documents based on the query.

3. **Language Model Preparation**:
   - Define a prompt template for the RAG model.
   - Create the PromptNode with the desired language model.

4. **Pipeline Creation**:
   - Build a pipeline to fit all the components together, including the retriever and prompt nodes.

5. **Experimentation**:
   - Prompt the pipeline with various queries to get answers from the dataset.
   - Evaluate the performance of the RAG model on the climate_fever dataset.

## Usage

To run the project:

1. Clone this repository:
git clone <repository_url>

2. Install the necessary dependencies:
pip install -r requirements.txt


3. Run the main script to execute the project:
python main.py


## References

- [Haystack Documentation](https://haystack.deepset.ai/)
- [Climate Fever Dataset](<link_to_dataset>)
