<a href="https://sambanova.ai/">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./images/SambaNova-light-logo-1.png" height="60">
  <img alt="SambaNova logo" src="./images/SambaNova-dark-logo-1.png" height="60">
</picture>
</a>

# SambaNova AI Starter Kits

# Overview

SambaNova AI Starter Kits are a collection of open-source examples and guides to facilitate the deployment of AI-driven use cases in the enterprise.

To run these examples, if you're a current SambaNova customer, you can deploy your models with SambaStudio. If you are not a SambaNova customer, you can self-service provision API endpoints using SambaNova Fast API or Sambaverse. Most code examples are written in Python, though the concepts can be applied in any language.

Questions? Just <a href="https://discord.gg/54bNAqRw" target="_blank">message us</a> on Discord <a href="https://discord.gg/54bNAqRw" target="_blank"><img src="https://github.com/sambanova/ai-starter-kit/assets/150964187/aef53b52-1dc0-4cbf-a3be-55048675f583" alt="Discord" width="22"/></a> or <a href="https://github.com/sambanova/ai-starter-kit/issues/new/choose" target="_blank">create an issue</a> in GitHub. We're happy to help live!

# Available AI Starter Kits

<table style="width: 100%;">
<thead>
<tr>
<th width="20%">Name</th>
<th width="50%">Kit Description</th>
<th width="15%">Compatible APIs</th>
<th width="15%">Category</th>
  
</tr>
</thead>
  
<tbody>

<tr>
<td width="20%"><a href="data_extraction/README.md">Data Extraction</a></td>
<td width="50%">Series of notebooks that demonstrate methods for extracting text from documents in different input formats.</td>
<td width="15%"> Sambaverse, SambaStudio, FastAPI </td>
<td width="15%"> Data Ingestion & Preparation </td>  
</tr>

<tr>
<td width="20%"><a href="yoda/README.md">YoDA: Your Data Your model</a></td>
<td width="50%">Sample training recipe to train a Language Model (LLM) using a customer's private data. </td>
<td width="15%"> SambaStudio </td>
<td width="15%"> Data Ingestion & Preparation </td>   
</tr>

<tr>
<td width="20%"><a href="fine_tuning_embeddings/README.md"> Fine tuning embeddings</a></td>
<td width="50%">Example workflow for fine-tuning embeddings from unstructured data, leveraging Large Language Models (LLMs) and open-source embedding models to enhance NLP task performance.</td>
<td width="15%">SambaStudio</td>
<td width="15%"> Model Development & Optimization </td>  
</tr>

<tr>
<td width="20%"><a href="fine_tuning_sql/README.md"> Fine tuning SQL</a></td>
<td width="50%">Example workflow for fine-tuning an SQL model for Question-Answering purposes, leveraging Large Language Models (LLMs) and open-source embedding models to enhance SQL generation task performance.</td>
<td width="15%">SambaStudio</td>
<td width="15%"> Model Development & Optimization </td>   
</tr>

<tr>
<td width="20%"><a href="prompt_engineering/README.md">Prompt Engineering</a></td>
</td>
<td width="50%">Starting point demo for prompt engineering using SambaNova's API to experiment with different use case templates. Provides useful resources to improve prompt crafting, making it an ideal entry point for those new to this AISK.</td>
<td width="15%">Sambaverse, SambaStudio, FastAPI</td>
<td width="15%"> Model Development & Optimization </td> 
</tr>

<tr>
<td width="20%"><a href="edgar_qna/README.md">EDGAR Q&A</a></td>
<td width="50%">Example workflow that uses the SambaNova platform to answer questions about organizations using their 10-K annual reports. Includes a runnable local demo and a Docker container to simplify remote deployment.</td>
<td width="15%">Sambaverse, SambaStudio, FastAPI</td>
<td width="15%"> Intelligent Information Retrieval </td>  
</tr>

<tr>
<td width="20%"><a href="enterprise_knowledge_retriever/README.md">Enterprise Knowledge Retrieval</a></td>
<td width="50%">Sample implementation of the semantic search workflow using the SambaNova platform to get answers to questions about your documents. Includes a runnable demo.</td>
<td width="15%">Sambaverse, SambaStudio, FastAPI</td>
<td width="15%"> Intelligent Information Retrieval </td>  
</tr>

<tr>
<td width="20%"><a href="image_search/README.md">Image Search</a></td>
<td width="50%">This example workflow shows a simple approach to image search by image description or image similarity. All workflows are built using the SambaNova platform. </td>
<td width="15%"> SambaStudio </td>
<td width="15%"> Intelligent Information Retrieval </td>   
</tr>

<tr>
<td width="20%"><a href="multimodal_knowledge_retriever/README.md">Multimodal Knowledge Retriever</a></td>
<td width="50%"> Sample implementation of the semantic search workflow leveraging the SambaNova platform to get answers using text, tables, and images to questions about your documents. Includes a runnable demo. </td>
<td width="15%"> Sambaverse, SambaStudio, FastAPI </td>
<td width="15%"> Intelligent Information Retrieval </td>   
</tr>

<tr>
<td width="20%"><a href="post_call_analysis/README.md">Post Call Analysis</a></td>
<td width="50%">Example workflow that shows a systematic approach to post-call analysis including Automatic Speech Recognition (ASR), diarization, large language model analysis, and retrieval augmented generation (RAG) workflows. All workflows are built using the SambaNova platform. </td>
<td width="15%">Sambaverse, SambaStudio, FastAPI</td>
<td width="15%"> Intelligent Information Retrieval </td>   
</tr>

<tr>
<td width="20%"><a href="eval_jumpstart/README.md">RAG Evaluation Kit</a></td>
<td width="50%">A tool for evaluating the performance of LLM APIs using the RAG Evaluation methodology.</td>
<td width="15%">Sambaverse, SambaStudio</td>
<td width="15%"> Intelligent Information Retrieval </td>  
</tr>

<tr>
<td width="20%"><a href="search_assistant/README.md">Search Assistant</a></td>
<td width="50%">Sample implementation of the semantic search workflow built using the SambaNova platform to get answers to your questions using search engine snippets, and website crawled information as the source. Includes a runnable demo.</td>
<td width="15%">Sambaverse, SambaStudio, FastAPI</td>
<td width="15%"> Intelligent Information Retrieval </td>   
</tr>

<tr>
<td width="20%"><a href="web_crawled_data_retriever/README.md">Web Crawled Data Retrieval</a></td>
<td width="50%">Sample implementation of a semantic search workflow built using the SambaNova platform to get answers to your questions using website crawled information as the source. Includes a runnable demo.</td>
<td width="15%">Sambaverse, SambaStudio, FastAPI</td>
<td width="15%"> Intelligent Information Retrieval </td>   
</tr>

<tr>
<td width="20%"><a href="agent_workflows/README.md">Agents with Langraph</a></td>
<td width="50%"> This kit demonstrates two types of agentic pipelines using LangGraph and SambaNova Systems APIs. One pipeline consists of a complex, Corrective RAG with Codegen that can answer singular or compound questions, with or without math. The other agentic pipeline, Corrective Rag Team, demonstrates how to orchestrate agents or teams of agents via a pipeline supervisor. It uses a Corrective RAG team and a Corrective Web Search team. </td>
<td width="15%"> SambaStudio </td>
<td width="15%"> Advanced AI Capabilities </td>  
</tr>

<tr>
<td width="20%"><a href="benchmarking/README.md">Benchmarking</a></td>
<td width="50%">This kit evaluates the performance of multiple LLM models hosted in SambaStudio. It offers various performance metrics and configuration options. Users can also see these metrics within a chat interface.</td>
<td width="15%"> SambaStudio, FastAPI</td>
<td width="15%"> Advanced AI Capabilities </td>    
</tr>

<tr>
<td width="20%"><a href="code_copilot/README.md">Code Copilot</a></td>
<td width="50%">This example guide shows a simple integration with Continue VSCode and JetBrains extension using SambaNova platforms, to use Sambanova's hosted models as your custom coding assistant. </td>
<td width="15%">Sambaverse, SambaStudio</td>
<td width="15%"> Advanced AI Capabilities </td>  
</tr>

<tr>
<td width="20%"><a href="CoE_jump_start/README.md">CoE jump start</a></td>
<td width="50%">This kit demonstrates how to call <a href=https://coe-1.cloud.snova.ai/>SambaNova CoE</a> models using the Langchain framework. The script offers different approaches for calling CoE models, including using Sambaverse, using SambaStudio with a named expert, and using SambaStudio with routing.</td>
<td width="15%">Sambaverse, SambaStudio</td>
<td width="15%"> Advanced AI Capabilities </td>  
</tr>

<tr>
<td width="20%"><a href="function_calling/README.md"> Function Calling</a></td>
<td width="50%">Example of tools calling implementation and a generic function calling module that can be used inside your application workflows.</td>
<td width="15%">Sambaverse, SambaStudio, FastAPI</td>
<td width="15%"> Advanced AI Capabilities </td>   
</tr>

</tbody>
</table>

# Get started with SambaNova AI starter kit

## Getting a SambaNova API key and setting your generative models

Currently, there are three ways to obtain an API key from SambaNova. If you're a current SambaNova customer, you can deploy your models with SambaStudio. If you are not a SambaNova customer, you can self-service provision API endpoints using SambaNova Fast API or Sambaverse. Note that Sambaverse, although freely available to the public, is rate limited and will not have fast RDU optimized inference speeds.

### Use SambaNova Fast API (Option 1)

SambaNova Fast API allows you to interact with multiple open-source models. You can find more information and get your API key on the [SambaNova Fast API webpage](https://sambanova.ai/fast-api).

Integrate SambaNova Fast API LLMs with this AI starter kit by updating the API information. These are represented as configurable variables in the environment variables file in `ai-starter-kit/.env`:

- Create the `.env` file at `ai-starter-kit/.env` if it doesn't exist.
- Enter the FastAPI URL and API key in the `.env` file, for example:
  
```bash
FASTAPI_URL = "https://fastapi.snova.ai/api/v1/chat/completion"
FASTAPI_API_KEY = "456789abcdef0123456789abcdef0123"
```

### Use Sambaverse (Option 2)

Sambaverse allows you to interact with multiple open-source models. You can view the list of available models and interact with them in the [Sambaverse playground](https://sambaverse.sambanova.ai/playground).

Please note that Sambaverse's free offering is performance-limited. Companies that are ready to evaluate the production tokens-per-second performance, volume throughput, and 10x lower total cost of ownership (TCO) of SambaNova should [contact us](https://sambaverse.sambanova.ai/contact-us) for a non-limited evaluation instance.

Begin by creating a [Sambaverse](https://sambaverse.sambanova.net) account, then [get your API key](https://docs.sambanova.ai/sambaverse/latest/use-sambaverse.html#_your_api_key) from the username button. Use the available models.

Integrate Sambaverse LLMs with this AI starter kit by updating the API information. These are represented as configurable variables in the environment variables file in `ai-starter-kit/.env`:

- Create the `.env` file at `ai-starter-kit/.env` if it doesn't exist.
- Enter the Sambaverse API key in the `.env` file, for example:

```bash
SAMBAVERSE_API_KEY="456789ab-cdef-0123-4567-89abcdef0123"
```

### Use SambaStudio (Option 3)

Begin by deploying your LLM of choice (e.g. Llama 3 8B) to an endpoint for inference in SambaStudio. Use either the GUI or CLI, as described in the [SambaStudio endpoint documentation](https://docs.sambanova.ai/sambastudio/latest/endpoints.html).

Integrate your LLM deployed on SambaStudio with this AI starter kit by updating the API information for the SambaNova LLM. These are represented as configurable variables in the environment variables file in `ai-starter-kit/.env`:

- Create the `.env` file at `ai-starter-kit/.env` if it doesn't exist.
- Set your SambaStudio variables. For example, an endpoint with the URL
"https://api-stage.sambanova.net/api/predict/nlp/12345678-9abc-def0-1234-56789abcdef0/456789ab-cdef-0123-4567-89abcdef0123"
is entered in the `.env` file as:

``` bash
SAMBASTUDIO_BASE_URL="https://api-stage.sambanova.net"
SAMBASTUDIO_BASE_URI="api/predict/generic"
SAMBASTUDIO_PROJECT_ID="12345678-9abc-def0-1234-56789abcdef0"
SAMBASTUDIO_ENDPOINT_ID="456789ab-cdef-0123-4567-89abcdef0123"
SAMBASTUDIO_API_KEY="89abcdef-0123-4567-89ab-cdef01234567"
```

## Setting your embedding models

Currently, you can set your embedding models on SambaStudio or CPU. 

### Use SambaStudio (Option 1)

You can use SambaStudio embedding model endpoints instead of the CPU-based HugginFace embeddings to increase inference speed. Please follow [this guide](https://docs.sambanova.ai/sambastudio/latest/e5-large.html#_deploy_an_e5_large_v2_endpoint) to deploy your SambaStudio embedding model.

Update API information for the SambaNova embedding endpoint. These are represented as configurable variables in the environment variables file in `ai-starter-kit/.env`:

- Create the `.env` file at `ai-starter-kit/.env` if it doesn't exist.
- Set your SambaStudio variables. For example, an endpoint with the URL
`"https://api-stage.sambanova.net/api/predict/generic/12345678-9abc-def0-1234-56789abcdef0/456789ab-cdef-0123-4567-89abcdef0123"`
is entered in the `.env` file as:

``` bash
SAMBASTUDIO_EMBEDDINGS_BASE_URL="https://api-stage.sambanova.net"
SAMBASTUDIO_EMBEDDINGS_BASE_URI="api/predict/generic"
SAMBASTUDIO_EMBEDDINGS_PROJECT_ID="12345678-9abc-def0-1234-56789abcdef0"
SAMBASTUDIO_EMBEDDINGS_ENDPOINT_ID="456789ab-cdef-0123-4567-89abcdef0123"
SAMBASTUDIO_EMBEDDINGS_API_KEY="89abcdef-0123-4567-89ab-cdef01234567"
```

### Use CPU (Option 2)

Alternatively, you can run the Hugging Face embedding models on CPU. In this case, no information is needed in the `.env` file.

## Run the desired starter kit

Go to the `README.md` of the starter kit you want to use and follow the instructions. See [Available AI Starter Kits](#available-ai-starter-kits).

## Additional information

<details>
<summary>Use Sambanova's LLMs and Langchain wrappers</summary>

### LLM Wrappers

Set your environment as shown in [integrate your model](#integrate-your-model-in-the-starter-kit).

#### Using Sambaverse LLMs

1. Import the **samabaverse** langchain community wrapper in your project and define your **Sambaverse** LLM:

```python
from langchain_community.llms.sambanova import Sambaverse

load_dotenv('.env')

llm = Sambaverse(
    sambaverse_model_name="Meta/Meta-Llama-3-8B-Instruct",
    model_kwargs={
      "do_sample": False,
      "temperature": 0.0,
      "max_tokens_to_generate": 512,
      "select_expert": "Meta-Llama-3-8B-Instruct",
      "process_prompt": "False"
      },
)
```

2. Use the model

```python
llm.invoke("your prompt")
```

#### Using Sambastudio LLMs

1. Import the **SambaStudio** langchain community wrapper in your project and define your **SambaStudio* LLM:

- If using a CoE endpoint:

```python
from langchain_community.llms.sambanova import SambaStudio

load_dotenv('.env')

llm = SambaStudio(
    model_kwargs={
      "do_sample": False,
      "max_tokens_to_generate": 512,
      "temperature": 0.0,
      "select_expert": "Meta-Llama-3-8B-Instruct",
      "process_prompt": "False"
      },
)
```

- If using a single model endpoint

```python
from langchain_community.llms.sambanova import SambaStudio

load_dotenv('.env')

llm = SambaStudio(
    model_kwargs={
      "do_sample": False,
      "max_tokens_to_generate": 512,
      "temperature": 0.0,
      "process_prompt": "False"
      },
)
```

2. Use the model

```python
llm.invoke("your prompt")
```

See [utils/usage.ipynb](./utils/usage.ipynb) for an example.

### Using SambaNova Fast-API LLMs

1. Import our **SambaNovaFastAPI** langchain internal wrapper in your project and define your **SambaNovaFastAPI** LLM:


```python
from util..model_wrappers.llms.langchain_llms import SambaNovaFastAPI

load_dotenv('.env')

llm = SambaNovaFastAPI(model='llama3-70b')
```

2. Use the model

```python
llm.invoke("your prompt")
```

See [utils/usage.ipynb](./utils/usage.ipynb) for an example.

### Embedding Wrapper

1. Import the **SambaStudioEmbedding** langchain community wrapper in your project and define your **SambaStudioEmbeddings** embedding:

- If using a CoE endpoint

```python
from langchain_community.embeddings import SambaStudioEmbeddings

load_dotenv('.env')

embedding = SambaStudioEmbeddings(
              batch_size=1,
              model_kwargs = {
                  "select_expert":e5-mistral-7b-instruct
                  }
              )
```

- If using a single embedding model endpoint

```python
from langchain_community.embeddings import SambaStudioEmbeddings

load_dotenv('.env')

embedding = SambaStudioEmbeddings(batch_size=32)
```

> Note that using different embedding models (cpu or sambastudio) may change the results, and change the way they are set and their parameters

2. Use your embedding model in your langchain pipeline

See [utils/usage.ipynb](./utils/usage.ipynb) for an example.

---

</details>

<details>
<summary>Setting up your virtual environment</summary><br/>

There are two approaches to setting up your virtual environment for the AI Starter Kits:

1. **Individual Kit Setup (Traditional Method)**
2. **Base Environment Setup (WIP)**

### 1. Individual Kit Setup

Each starter kit has its own `README.md` and `requirements.txt` file. You can set up a separate virtual environment for each kit by following the instructions in their respective directories. This method is suitable if you're only interested in running a single kit or prefer isolated environments for each project.

To use this method:
1. Navigate to the specific kit's directory
2. Create a virtual environment
3. Install the requirements
4. Follow the kit-specific instructions

### 2. Base Environment Setup 

For users who plan to work with multiple kits or prefer a unified development environment, we recommend setting up a base environment. This approach uses a Makefile to automate the setup of a consistent Python environment that works across all kits.

Benefits of the base environment approach:
- Consistent Python version across all kits
- Centralized dependency management
- Simplified setup process
- Easier switching between different kits

#### Prerequisites

- **pyenv**: The Makefile will attempt to install pyenv if it's not already installed.
- **Docker**: (Optional) If you want to use the Docker-based setup, ensure Docker is installed on your system.

#### What the Base Setup Does

1. Installs pyenv and Poetry if they are not already installed.
2. Sets up a Python virtual environment using a specified Python version (default is 3.11.3).
3. Installs all necessary dependencies for the base environment.
4. Sets up the parsing service required by some kits.
5. Installs system dependencies like Tesseract OCR and Poppler.
6. Provides Docker-based setup options for consistent environments across different systems.



#### Setting Up the Base Environment


1. **Install and Set Up the Base Environment:**

```bash
make all
```
This command will set up the base ai-starter-kit environment, including installing all necessary tools and dependencies.

2. **Activate the Base Environment:**

```bash
source .venv/bin/activate
```

3. **Navigate to Your Chosen Starter Kit:**
```bash
cd path/to/starter_kit
```
Within the starter kit there will be instructions on how to start the kit. You can skip the virtual environment creation 
part in the kits README.md as we've done it here.



### Parsing Service Management
For certain kits, we utilise a standard parsing service. By Default it's started automatically with the base environment. To work with this service in isolation, following the steps in this section.

- **Start Parsing Service:**
```bash
make start-parsing-service
```

- **Stop Parsing Service:**
```bash
make stop-parsing-service
```

- **Check Parsing Service Status:**
```bash
make parsing-status
```

- **View Parsing Service Logs:**
```bash
make parsing-log
```

### Docker-based Setup

To use the Docker-based setup:

1. Ensure Docker is installed on your system.
2. Build the Docker image:

```bash
make docker-build
```

3. Run a specific kit in the Docker container:
```bash
make docker-run-kit KIT=<kit_name>
```
Replace `<kit_name>` with the name of the starter kit you want to run (e.g., `function_calling`).

4. To open a shell in the Docker container:
```bash
make docker-shell
```

### Cleanup

To clean up all virtual environments created by the makefile and stop parsing services run the following command:
```bash
make clean
```
This command removes all virtual environments created with the makefile, stops the parsing service, and cleans up any temporary files.
</details>

<details>
<summary>Troubleshooting</summary><br/>

If you encounter issues while setting up or running the AI Starter Kit, here are some common problems and their solutions:

### Python version issues

If you're having problems with Python versions:

1. Ensure you have pyenv installed: `make ensure-pyenv`
2. Install the required Python versions: `make install-python-versions`
3. If issues persist, check your system's Python installation and PATH settings.

### Dependency conflicts

If you're experiencing dependency conflicts:

1. Try cleaning your environment: `make clean`
2. Update the lock file: `poetry lock --no-update`
3. Reinstall dependencies: `make install`

### pikepdf installation issues

If you encounter an error while installing `pikepdf`, such as:

```
ERROR: Failed building wheel for pikepdf
Failed to build pikepdf
```

This is likely due to missing `qpdf` dependency. The Makefile should automatically install `qpdf` for you, but if you're still encountering issues:

1. Ensure you have proper permissions to install system packages.
2. If you're on macOS, you can manually install `qpdf` using Homebrew:
   ```bash
   brew install qpdf
   ```
3. On Linux, you can install it using your package manager, e.g., on Ubuntu:
   ```
   sudo apt-get update && sudo apt-get install -y qpdf
   ```
4. After installing `qpdf`, try running `make install` again.

If you continue to face issues, please ensure your system meets all the requirements for building `pikepdf` and consider checking the [pikepdf documentation](https://pikepdf.readthedocs.io/en/latest/installation.html) for more detailed installation instructions.


### Parsing service issues

If the parsing service isn't starting or is behaving unexpectedly:

1. Check its status: `make parsing-status`
2. View its logs: `make parsing-log`
3. Try stopping and restarting it: `make stop-parsing-service` followed by `make start-parsing-service`

### System Dependencies Issues

If you encounter issues related to Tesseract OCR or Poppler:

1. Ensure the Makefile has successfully installed these dependencies.
2. On macOS, you can manually install them using Homebrew:
 ```bash
   brew install tesseract poppler
   ```
3. On Linux (Ubuntu/Debian), you can install them manually:
 ```bash
   sudo apt-get update && sudo apt-get install -y tesseract-ocr poppler-utils
   ```
4. On Windows, you may need to install these dependencies manually and ensure they are in your system PATH.

### Docker-related Issues

If you're using the Docker-based setup and encounter issues:

1. Ensure Docker is properly installed and running on your system.
2. Try rebuilding the Docker image: `make docker-build`
3. Check Docker logs for any error messages.
4. Ensure your firewall or antivirus is not blocking Docker operations.

### General troubleshooting steps

1. Ensure all prerequisites (Python, pyenv, Poetry) are correctly installed.
2. Try cleaning and rebuilding the environment: `make clean all`
3. Check for any error messages in the console output and address them specifically.
4. Ensure your `.env` file is correctly set up in the ai-starter-kit root with all necessary environment variables.

If you continue to experience issues, please [open an issue](https://github.com/sambanova/ai-starter-kit/issues/new) with details about your environment, the full error message, and steps to reproduce the problem.

### Important Notes for Users

- Ensure you have sufficient permissions to install software on your system.
- The setup process may take several minutes, especially when installing Python versions or large dependencies.
- If you encounter any issues during setup, check the error messages and ensure your system meets all prerequisites.
- Always activate the base environment before navigating to and running a specific starter kit.
- Some kits may require additional setup steps. Always refer to the specific README of the kit you're using.
</details>

**Note:** These AI Starter Kit code samples are provided "as-is," and are not production-ready or supported code. Bugfix/support will be on a best-effort basis only. Code may use third-party open-source software. You are responsible for performing due diligence per your organization policies for use in your applications.
