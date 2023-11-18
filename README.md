# ChatGPT Clone with Fine-Tuned "microsoft/phi-1_5" Model

## Overview
This project is a ChatGPT clone built by fine-tuning the "microsoft/phi-1_5" language model on a new dataset. The fine-tuned model is deployed in a React-based web application, allowing users to interact with the chatbot.

## Fine-Tuning
The fine-tuning process involves training the "microsoft/phi-1_5" model on a specific dataset tailored for the chatbot's intended use. The fine-tuned model is then used to generate contextually relevant responses during interactions.

## Deployment
- Node.js
- React
- Flask (for serving the fine-tuned model)

### Requirements

```bash

pip install requirements.txt

```

### Steps

1. **Fine-Tuning the Model**
   - Refer to the fine-tuning script in the `fine_tuning/` directory.
   - Fine-tune the "microsoft/phi-1_5" model on your custom dataset.

2. **Set Up Flask API**
   - Use the Flask API in the `flask_api/` directory to serve the fine-tuned model.
   - Install required dependencies: `pip install flask transformers`.

3. **Deploy React Application**
   - Navigate to the `react_app/` directory.
   - Install dependencies: `npm install`.
   - Start the React application: `npm start`.

4. **Interaction**
   - Access the React application in a web browser.
   - Users can input messages, and the chatbot will respond based on the fine-tuned model.

## Project Structure

### `fine_tuning/`
Contains scripts and code for fine-tuning the "microsoft/phi-1_5" model on a custom dataset.

### `flask_api/`
Includes the Flask API for serving the fine-tuned model.

### `react_app/`
Houses the React-based web application for user interaction with the chatbot.

### `utils/`
Utility scripts and functions used across the project.

## Configuration
Adjust configuration parameters in the respective `config` files to customize the behavior of the fine-tuned model and the React application.

## Future Improvements
- Implement user authentication for personalized interactions.
- Enhance the React UI for a more seamless user experience.
- Explore continuous fine-tuning for improved adaptability to evolving conversational patterns.

## Contributors
- Adelard Dcunha

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to contribute, open issues, or suggest improvements!