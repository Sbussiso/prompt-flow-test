# Barfi Streamlit App with AWS Bedrock

This is a Streamlit application that provides a user-friendly interface for interacting with various language models and tools using the AWS Bedrock platform. The app allows users to create and manage prompt templates, test prompts with different models, and visualize the results using the Barfi block-based interface.

## Introduction

The Barfi Streamlit App is designed to simplify the process of working with language models and tools. It provides a visual interface for creating and managing prompt templates, testing prompts with different models, and integrating various tools such as web search, PubMed search, and Wikipedia search.

The app leverages the power of AWS Bedrock, a platform that provides access to a wide range of language models and tools. By integrating with AWS Bedrock, the app allows users to easily switch between different models and explore their capabilities.

## Features

- **Prompt Template Management**: Create, save, and manage prompt templates with placeholders for easy reuse.
- **Prompt Testing**: Test prompts with different language models and adjust parameters like temperature.
- **Barfi Block-based Interface**: Visualize and interact with the app using the Barfi block-based interface, allowing for easy flow creation and data manipulation.
- **Tool Integration**: Integrate various tools such as web search, PubMed search, and Wikipedia search to enhance the capabilities of the language models.
- **User Authentication**: Secure access to the app with user authentication using AWS Lambda functions.

## Installation

To run the Barfi Streamlit App locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your-repo/barfi-streamlit-app.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Set up the necessary AWS credentials and secrets in the `streamlit/secrets.toml` file.

4. Run the Streamlit app:

```bash
streamlit run app.py
```

## Usage

1. Launch the Barfi Streamlit App by running `streamlit run app.py`.
2. If you are not logged in, you will be prompted to enter your username and password on the login page.
3. After successful login, you will be redirected to the main app page.
4. On the main app page, you can create and manage prompt templates, test prompts with different models, and interact with the Barfi block-based interface.
5. Use the "Prompt Templates" button in the sidebar to navigate to the prompt templates page, where you can create, save, and manage prompt templates.
6. On the prompt templates page, enter a template name, prompt template with placeholders, and placeholder values in JSON format.
7. Click the "Save Template" button to save the template for future use.
8. Back on the main app page, you can select a saved template from the dropdown and test it with different models and tools.
9. The Barfi block-based interface allows you to visualize and manipulate the data flow, integrating various tools and models.
10. Use the "Logout" button in the sidebar to log out of the app.

## Contributing

Contributions to the Barfi Streamlit App are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.

When contributing, please follow these guidelines:

1. Fork the repository and create a new branch for your feature or bug fix.
2. Make your changes and ensure that the code follows the project's coding style and conventions.
3. Write tests for your changes, if applicable.
4. Update the documentation if necessary.
5. Submit a pull request with a clear description of your changes.

## License

This project is licensed under the [MIT License](LICENSE).