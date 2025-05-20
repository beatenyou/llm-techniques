# LLM Techniques
<p align="center">
    <img src="https://github.com/beatenyou/llm-techniques/blob/main/voyage.png">
p>

## LLM techniques from - mastering LLM engineering course
This repository takes a clear, hands-on approach for learning LLM and Agent development, breaking down advanced techniques into straightforward, understandable implementations. The scripts are modified exercises devliverables from Ed Donner's LLM Engineering course https://github.com/ed-donner/llm_engineering

My goal is simple: provide code that is readable, modifiable, and educational.

### 1) Basics
1. **Install Git** (if not already install) https://git-scm.com/download/win
  * Run the installer and follow the prompts, using default options
2. **Open Command Prompt** - Press Win + R, type `cmd`
3. **Navigate to your projects folder**
If you don't have one, create it
4. **Clone the repository**
In your Projects folder
`git clone https://github.com/beatenyou/llm-techniques.git`
`cd llm-techniques`
### 2) Environment
1. **Install Anaconda** https://docs.anaconda.com/anaconda/install/windows/
Run the installer and follow the prompts. Note: it takes a while to install
2. **Setup the enviornment**
Open **Anaconda Prompt**
  * Navigate to the "project root directory", could look like this `cd C:\Users\YourUsername\Documents\Projects\llm_techniques`
  * Create the environment with the project dependencies `conda env create -f environment.yml`
  * Wait for a few minutes for all packages to be installed
  * Activate with `conda activate llms`
You should see `(llms)` in your prompt, which indicates you've activated your new environment.
3. **Start Jupyter Lab**
  * In an Anaconda Prompt, from within the `llm_techniques` folder, type: `jupyter lab`
Jupyter Lab should open up in a browser
### **Alternative Install**
  * Install Python 3.11 https://www.python.org/downloads/
  * Navigate to the "project root directory", could look like this `cd C:\Users\YourUsername\Documents\Projects\llm_techniques`
  * Then, create a new virtual environment with this command: `python -m venv llms`
  * Activate the virtual environment with `llms\Scripts\activate` you should see (llms) in your command prompt
  * Run `python -m pip install --upgrade pip` followed by `pip install -r requirements.txt`
#### **Start Jupyter Lab**
  * From within the `llm_techniques` folder, type: `jupyter lab`
Jupyter Lab should open up in a browser
