# Description Generator

## Overview

This project is a simple description generator that utilizes the OpenAI API and the LangChain library. The user can input prompts into a Streamlit app, and the app generates a description about the person along with important events that happened on their birth date.

## Features

- Generates descriptions about people and significant events on their birth date.
- Utilizes the OpenAI API for natural language processing.
- Easy-to-use Streamlit app interface.
- Customizable with your own OpenAI API key.

## Getting Started

1. **Clone the Repository**: Clone this repository to your local machine using the following command:
   ```
   git clone https://github.com/your-username/description-generator.git
   ```

2. **Install Dependencies**: Navigate to the project directory and install the required dependencies using Conda. Make sure you have Conda installed on your system.
   ```
   conda env create -f environment.yml
   ```

3. **Set up OpenAI API Key**: Replace the placeholder API key in `constants.py` with your own OpenAI API key.

4. **Run the Application**: Run the example script `example1.py` and follow the prompts.
   ```
   python example1.py
   ```

## Example

Here's an example of how to use the application:

```python
# Import the DescriptionGenerator class
from description_generator import DescriptionGenerator

# Create an instance of DescriptionGenerator
generator = DescriptionGenerator()

# Set the prompt
prompt = "Describe Albert Einstein and the significant events on his birth date."

# Generate the description
description = generator.generate_description(prompt)

# Print the description
print(description)
```

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, feel free to open an issue or create a pull request.

