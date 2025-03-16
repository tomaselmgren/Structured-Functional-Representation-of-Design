# Structured Functional Representation of Design

## How to use this program

### Jupyter Notebook

This project uses Jupyter Notebook. You can install it using:
`pip install jupyter`

Run the notebook using:
`jupyter notebook main.ipynb` 

### Install the requirements

This project only has one requirement except for Python, pip, and Jupyter Notebook. Install it using the following command:
`pip install -r requirements.txt`

### OpenAI API

To run the algorithm, an OpenAI API key is required. You can get your own in the [OpenAI Developer Platform](https://platform.openai.com/docs/overview).

Once you have your API key, open the main.ipynb file, and add your API key in the constructor of the StructuredDesign class:

`self.client = OpenAI(api_key="")`

### Your Data

To test out the algorithm with your own data, scroll down to the bottom of the code cell. Above Step 1, you find a variable called `document_text = r"""Your text here"""`. Replace "Your text here" with the raw text contents of your file. 

You can also modify the `n` parameter to the function calls to get more FRs and DPs per level.

### Running the algorithm

Once you've completed the above steps, press the play button in the Jupyter Notebook interface, and wait for the results.
