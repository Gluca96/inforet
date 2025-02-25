# InfoRet Project

This project requires the installation of the packages listed in `requirements.txt` and Ollama. Follow the steps below to set up the environment and download the `deepseek-r1:8b` model before running the project.

## Requirements

- Python 3.10 or higher
- Ollama

## Installation

1. Clone the repository:

    ```sh
    git clone <put url here>
    cd inforet_proj
    ```

2. Install the required packages:

    ```sh
    pip install -r requirements.txt
    ```

3. Install Ollama by following the instructions on the [official Ollama website](https://ollama.com).

## Download the `deepseek-r1:8b` model

Before running the project, you need to download the `deepseek-r1:8b` model. Follow these steps:

1. Make sure Ollama is running:

    ```sh
    ollama serve
    ```

2. Download the `deepseek-r1:8b` model:

    ```sh
    ollama pull deepseek-r1:8b
    ```

## Running the project

Once the above steps are completed, you can run the notebooks in the project folders *demo*

Even tho all the necessary files to run any notebook are provided, to reproduce the experiment the notebooks have to be runned in the following oreder:
- data_generation
- data_analysis
- data_visualization