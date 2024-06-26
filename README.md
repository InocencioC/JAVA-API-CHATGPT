```markdown
# ChatGPT API Integration 🤖

This project demonstrates how to integrate the OpenAI ChatGPT API using Java. It allows you to send messages to ChatGPT and receive responses, leveraging the `gpt-3.5-turbo` model.

## Table of Contents 📋

- [Description](#description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [System Requirements](#system-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Description 📝

This Java application sends a user message to the OpenAI ChatGPT API and retrieves a response. The response is extracted and displayed to the user. This project serves as an example of how to interact with the OpenAI API using Java's `HttpURLConnection`.

## Features ✨

- Send a message to the ChatGPT API.
- Receive and display the response from the API.

## Technologies Used 💻

- Java
- OpenAI ChatGPT API

## System Requirements 🛠️

- Java Development Kit (JDK) 8 or higher
- Internet connection for API access

## Installation 🔧

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/JAVA-API-CHATGPT.git
    cd JAVA-API-CHATGPT
    ```

2. **Open the project in your preferred Java IDE**.

3. **Set your OpenAI API key**:
    - Replace the placeholder `"YOUR KEY HERE"` with your actual OpenAI API key in the `chatGPT` method:
    ```java
    // String apiKey = "YOUR KEY HERE";
    ```

## Usage 🚀

1. **Run the application**:
    - Execute the `Main` class. It will send a predefined message ("Talk about naruto?") to the ChatGPT API and print the response.

2. **Modify the message**:
    - Change the message in the `main` method to send different queries to the API:
    ```java
    System.out.println(chatGPT("Your custom message here"));
    ```

## Contributing 🤝

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a Pull Request.

## License 📄

This project is licensed under the MIT License. See the [LICENSE] file for more information.

## Contact 📬

For any questions or inquiries, please contact inocenciocordeiroarmando@hotmail.com.
```
