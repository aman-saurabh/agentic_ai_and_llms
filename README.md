![AgenticAI And LLMs](https://img.shields.io/badge/AgenticAI%20And%20LLMs%20%20%20|%20%20version-gray?style=flat)![v1.0.0](https://img.shields.io/badge/1.0.0-brightgreen?style=flat)

# A Sample project to demonstrate working of Agentic AI and LLMs

## Initial Setup
Copy following files in your project :
* pyproject.toml
* uv.lock
* requirement.txt(Optional)

## Command to create virtual environment and install dependencies
```
uv sync
```

## Add OpenAI key in the ".env" file: 
Create a ".env" file in the project directory and add the OpenAI key in the file as follows.
```
OPENAI_API_KEY=your_openai_api_key_here
```

## creating .ipynb file and setting kernel for the file :
Create openai_webscraper.ipynb file and set kernel by clicking on "Select kernel"(On the top right corner of the file), then in the Pop-up select "Python Environment" and then select ".venv"(i.e. the virtual environment "uv" created for you). It will set the kernel for you and now in place of "Select kernel" you will see ".venv(Python 3.12.13)" or something similar. It means kernel is set for the file.

## How to add code in a cell in ".ipynb" file :
In the ".ipynb" file click on the "+ Code" button to add a cell 

## How to run a cell :
When you hover over a cell it shows a "horizontal triangle" symbol. If you hover over that triangle it shows the text "Execute cell". Click on this triangle to run the cell.

## How to run all cells i.e. complete file programs :
On the Top you will see a "Horizoontal double triangle" symbol folled by "Run all". Cick on this button to run complete program.

We can also run complete program from the terminal using following command :
```
jupyter nbconvert --to notebook --execute openai_webscraper.ipynb --inplace
```


## 👤 Author

**Aman Saurabh**  
💼 GitHub: [@aman-saurabh](https://github.com/aman-saurabh)  