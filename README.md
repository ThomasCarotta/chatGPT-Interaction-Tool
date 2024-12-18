```markdown
# ChatGPT Interaction Tool

This Python project provides a module for interacting with the ChatGPT model via the OpenAI API. It allows users to send queries and receive responses in a conversational format. The program includes a command-line interface with a conversation mode that facilitates dynamic interactions, query editing, and error handling.

## Features

- **Conversation Mode**: Activate conversation mode by passing the `--convers` argument when running the script. This mode continuously processes user input and provides responses from ChatGPT.
- **Query Processing**: Users can send queries to the ChatGPT model and receive detailed responses. Each query and response is stored for reference during the session.
- **Last Query Editing**: Users can edit their last query by pressing the "Up Arrow" key, enabling quick refinements and resubmissions.
- **Error Handling**: The program captures exceptions and provides clear error messages to help identify and resolve issues during execution.

## How to Run

To run the program in conversation mode, use the following command:

```bash
python your_script.py --convers
```

If you prefer to run the program without activating conversation mode, simply use:

```bash
python your_script.py
```

## Requirements

- **Python 3.x**: Ensure you have Python 3 installed on your system.
- **OpenAI Python Package**: Install the `openai` package by running:

  ```bash
  pip install openai
  ```

- Replace the placeholder `None` in the script with your own OpenAI API key for proper functionality:

  ```python
  client = OpenAI(api_key="your_api_key_here")
  ```

## Usage

1. **Input Queries**: Enter your queries in the terminal when the program is running.
2. **Edit Last Query**: Use the "Up Arrow" key to recall and modify the last query, then resubmit it for processing.
3. **View Responses**: The program displays the model's response to each query in real time.
4. **Error Feedback**: If an error occurs (e.g., invalid API key or connectivity issues), a helpful error message will be displayed.

## Notes

- Ensure your OpenAI API key is valid and has sufficient quota for usage.
- The `temperature`, `max_tokens`, and other parameters in the script can be adjusted to modify the behavior of the model as needed.
- Press `Ctrl + C` to exit the program at any time.

Enjoy seamless interaction with ChatGPT through this lightweight and efficient tool!
```
