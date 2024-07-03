# MISTRAL WEB UI

![Mistral Logo](./images/chatbot.png)

## Overview
This is a simple web user interface (UI) for interacting with Mistral, built using vanilla JavaScript.
I have hosted the Mistral Server onn AWS gdn4.xlarge instance it costs about $0.50/hr that is pretty decent just for testing purposes. And if you have a GPU that can handle the workload I would preffer to run Ollama locally.

## Setup
1. **Set Host IP:** At the top of `script.js`, specify the `HOST_IP` where Mistral is hosted:
    ```javascript
    const HOST_IP = ''; // Add your server's public IP or '127.0.0.1' for local machine
    ```
2. **Default Port:** Mistral runs by default on port 11434. You typically won't need to change this setting.

## Usage
Open `index.html` in a web browser. Ensure Mistral server is running and accessible at the specified `HOST_IP`.

## Contributing
Contributions are welcome! If you'd like to improve this project:

- Fork the repository
- Create your feature branch (`git checkout -b feature/AmazingFeature`)
- Commit your changes (`git commit -am 'Add some AmazingFeature'`)
- Push to the branch (`git push origin feature/AmazingFeature`)
- Open a pull request

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.

### Notes:
- **Overview:** Provides a brief introduction to the project.
- **Setup:** Clearly explains how to configure `HOST_IP` in `script.js`.
- **Usage:** Gives simple instructions for using the web interface.
- **Contributing:** Encourages contributions and outlines the basic steps.

Feel free to adjust any details or sections based on your specific project needs!