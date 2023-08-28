# Querybot

Querybot is a Large Language Model (LLM) application powered by Meta's LLaMA-2 model, designed to answer questions related to the content of various sources. It can provide information within certain limits and also suggest relevant websites available on the internet to the best of its ability.

This project specifically utilizes the TheBloke/Llama-2-7b-Chat-GPTQ quantized model from the Hugging Face model hub. The quantized model enhances performance on systems with limited GPU RAM, resulting in faster inference times.

## Example

![Querybot Example](https://github.com/Pyasma/Querybot/assets/94688939/1455404d-3a65-4c9a-b0ed-550f09d4dec4)

## Usage

### 1. Colab Notebook (Recommended)

Running this project through a Colab notebook is the simplest method.

1. Locate the `Querybot.ipynb` file in this repository.
2. Click the "Open in Colab" button at the top of the file.
3. Change the runtime type to T4 GPU.
4. Run all the cells in the notebook.

### 2. Local Setup (GPU with at least 8GB RAM)

If you want to perform inference locally, ensure you have a GPU with a minimum of 8GB of RAM.

#### Instructions:

1. Clone this repository to your local machine.
   ```shell
   git clone https://github.com/Pyasma/Querybot
2. Navigate to the project directory
    ```shell
   cd Querybot
3. Install the required dependencies
   ```shell
   pip install -r requirements.txt
4. Run the 'app.py' file
    ```shell
   python app.py


You can place this [content](https://github.com/Pyasma/Querybot) in your README file to provide detailed instructions to users on how to use the [Querybot](https://github.com/Pyasma/Querybot) project and understand its [licensing](https://github.com/Pyasma/Querybot/blob/main/LICENSE) terms.



## License
This project is licensed under the [Apache License 2.0](LICENSE). Please see the [`LICENSE`](LICENSE) file for more details.
