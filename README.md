# Multi-modal LLM for CadQuery Code Generation

## 🌟 Idea

The core idea of this project is to leverage a Multi-modal Large Language Model (LLM) to achieve the goal of automated CadQuery code generation from visual inputs (images) and text prompts.

## 🚀 Workflow

Our approach is structured into the following key phases:

1.  **Data Extraction:** Gather and prepare the necessary data from specified sources, primarily image-code pairs.
2.  **Preliminary EDA & Feature Identification:** Conduct an initial Exploratory Data Analysis to understand the dataset characteristics and identify important features crucial for the model's learning.
3.  **Model & Library Setup:** Download the chosen multi-modal models and install all required libraries and dependencies to set up the development environment.
4.  **Multimodal Input Tokenization:** Implement a robust tokenization pipeline that effectively combines both text (prompts and target code) and image data into a unified multi-modal input format suitable for the LLM.

## 🧪 Experiments Conducted

During the development process, the following experiments and considerations were undertaken:

* **Model Selection:** Explored and considered `MiniCPM` and `LLaVA` models, prioritizing those that offer a balance between performance and memory efficiency to avoid resource limitations.
* **Deadlock Resolution:** Progressed through the development, actively addressing and resolving deadlocks encountered during the process.

## ✨ Results

The initial efforts have yielded promising insights:

* The established workflow aligns well with the desired project goals of image-to-code generation.
* Despite challenges, continuous effort led to the successful identification and resolution of various errors encountered during implementation.

## 🚧 Challenges, Shortcomings & Key Learnings

This project presented valuable learning opportunities and challenges:

* **Resource Constraints:** Faced significant memory issues, necessitating a transition from a local development environment to Google Colab. This highlighted the substantial computational demands of fine-tuning large language models.
* **LLM Fine-tuning Proficiency:** Gained a much deeper and practical understanding of how to effectively fine-tune an LLM, especially in the context of a real-time, practical use case like code generation.
