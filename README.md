# Sho'tLeftDomains

Sho'tLeftDomains is an Android application that leverages AI to provide interactive chat responses using the OpenAI GPT-3 API. This app allows users to enter prompts and receive generated responses, making it an engaging and innovative way to interact with AI technology.

## Inspiration

The inspiration for Sho'tLeftDomains comes from the desire to combine AI and blockchain technologies to create a unique, interactive user experience. By integrating Amazon's Kendra and Unstoppable Domains APIs, the app aims to explore the synergy between AI and Web3 space, providing insightful interactions and personalized user experiences.

## What it does

Sho'tLeftDomains allows users to:
- Enter text prompts
- Send these prompts to the OpenAI GPT-3 API
- Display the generated AI responses

## How we built it

The application is built using:
- **Android Studio**: The primary IDE for Android development
- **Java**: The programming language used for Android app development
- **Volley**: An HTTP library that makes networking for Android apps easier and faster
- **Gson**: A library for converting Java objects to JSON and vice versa
- **OpenAI GPT-3 API**: For generating AI responses based on user prompts

### Layout

The app consists of a simple UI with:
- An `EditText` for entering prompts
- A `Button` to send the prompt
- A `TextView` to display the response

## Challenges we ran into

- Integrating the OpenAI API and handling the responses efficiently
- Ensuring secure handling of API keys
- Designing a user-friendly interface

## Accomplishments that we're proud of

- Successfully integrating OpenAI's GPT-3 API into an Android application
- Creating a smooth and interactive user experience
- Ensuring efficient and secure API communication

## What we learned

- How to integrate third-party APIs into Android applications
- The importance of secure API key management
- Best practices for Android UI/UX design

## What's next for Sho'tLeftDomains

- Integrating Amazon Kendra for enhanced search capabilities
- Adding Unstoppable Domains resolution for blockchain integration
- Enhancing the UI/UX with more interactive elements
- Expanding functionality to include wallet analysis and AI-driven domain management

## Built with

- **Languages**: Java
- **Frameworks**: Android SDK
- **Libraries**: Volley, Gson
- **APIs**: OpenAI GPT-3

## Getting Started

### Prerequisites

- Android Studio installed on your development machine
- An OpenAI API key

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/shotleftdomains.git
    ```

2. Open the project in Android Studio.

3. Add your OpenAI API key:
    - Replace `"your_openai_api_key"` in `MainActivity.java` with your actual API key.

4. Build and run the project on your Android device or emulator.

## Usage

1. Launch the Sho'tLeftDomains app.
2. Enter a prompt in the input field.
3. Press the "Send" button.
4. View the generated response in the response view.

## Contributing

We welcome contributions to enhance Sho'tLeftDomains. Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.
