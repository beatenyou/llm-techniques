# LLM Techniques
<img src="https://github.com/beatenyou/llm-techniques/blob/main/voyage.png" />

## LLM techniques from - mastering LLM engineering course
This repository takes a clear, hands-on approach for learning LLM and Agent development, breaking down advanced techniques into straightforward, understandable implementations. The scripts are modified exercises devliverables from Ed Donner's LLM Engineering course https://github.com/ed-donner/llm_engineering

My goal is simple: provide code that is readable, modifiable, and educational.

### Part 1. Clone the Repo
Local copy of the code
1. **Install Git** (if not already install)
  * Download Git from https://git-scm.com/download/win
  * Run the installer and follow the prompts, using default options
  * After the installation, you may need to open a new Powershell window to use it (or you might even need to restart)
2. **Open Command Prompt**
  * Press Win + R, type `cmd`, and press Enter
3. **Navigate to your projects folder**
If you have a specific folder for projects, navigate to it using the cd command. For example:
`cd C:\Users\YourUsername\Documents\Projects`
Replacing YourUsername with your actual Windows user

If you don't have a projects folder, you can create one:
`mkdir C:\Users\YourUsername\Documents\Projects`  
`cd C:\Users\YourUsername\Documents\Projects`
   
4. **Clone the repository**
Enter this in the command prompt in the Projects folder
`https://github.com/beatenyou/llm-techniques.git`
`cd llm-techniques`
### Part 2. Install Anaconda environment
1. **Install Anaconda**
  * Download Anaconda from https://docs.anaconda.com/anaconda/install/windows/
Run the installer and follow the prompts. Note that it takes up several GB and takes a while to install, but it will be a powerful platform for future use.
2. **Setup the enviornment**
Open **Anaconda Prompt**
  * Navigate to the "project root directory" by entering something like `cd C:\Users\YourUsername\Documents\Projects\llm_techniques` using the actual path to the llm_techniques project root directory.
  * Create the environment: `conda env create -f environment.yml`
  * Wait for a few minutes for all packages to be installed
  * You have now built an isolated, dedicated AI environment for running LLMs, vector datastores, and so much more! You now need to activate it using this command: `conda activate llms`
You should see `(llms)` in your prompt, which indicates you've activated your new environment.
3. **Start Jupyter Lab**
  * In the Anaconda Prompt, from within the `llm_techniques` folder, type: `jupyter lab`
Jupyter Lab should open up in a browser
### **Alternative**
  * Install Python 3.11 https://www.python.org/downloads/
  * Navigate to the "project root directory" by entering something like `cd C:\Users\YourUsername\Documents\Projects\llm_techniques` using the actual path to the llm_techniques project root directory.
  * Then, create a new virtual environment with this command: `python -m venv llms`
  * Activate the virtual environment with `llms\Scripts\activate` you should see (llms) in your command prompt
  * Run `python -m pip install --upgrade pip` followed by `pip install -r requirements.txt`
#### **Start Jupyter Lab**
  * From within the `llm_techniques` folder, type: `jupyter lab`
The click on any `.ipynb` file
