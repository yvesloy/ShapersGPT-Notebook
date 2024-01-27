# ShapersGPT

ShapersGPT is a cutting-edge tool that integrates the power of GPT-4 with the wealth of knowledge found on the World Economic Forum and Global Shapers community websites. By harnessing a Google Custom Search Engine, ShapersGPT sifts through the content of these sites to find the most relevant information before feeding it into OpenAI's GPT-4 model. The answers generated are beautifully formatted in Markdown for readability and easy integration into other platforms.

## Installation

ShapersGPT uses pipenv for managing project dependencies. Ensure you have pipenv installed; if not, you can install it with pip:

```bash
pip install pipenv
```

Once pipenv is installed, setting up ShapersGPT is as simple as running:

```bash
pipenv install
```
This command will install all the necessary dependencies as specified in the Pipfile.

## Features

- Custom Search Integration: Utilizes a Google Custom Search Engine to perform targeted searches on https://www.weforum.org and http://globalshapers.org.
- GPT-4 Integration: Feeds the top search result into OpenAI's GPT-4 model to generate an informed response.
- Markdown Formatting: Formats the GPT-4 response in Markdown for clarity and ease of use.

## Contributing
We welcome contributions to ShapersGPT! If you have suggestions or improvements, please fork the repository and submit a pull request.

