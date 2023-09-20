# Flutter ChatGPT App

This is a Flutter-based chat application that integrates with OpenAI's GPT-3.5 Turbo model to provide chatbot functionality.

## Features

- Chat interface with user and ChatGPT roles.
- Integration with OpenAI API for chat completions.
- Stream and non-stream chat request options.
- Animation effects for chat messages.
- Clear chat history option.

## Setup

### Dependencies

The app uses the following dependencies:

- `http`: For making API requests.
- `vibration`: To provide haptic feedback.
- `rxdart`: For reactive programming.
- `envied`: For environment variable management.

### API Key Configuration

This app uses the [`ENVied`](https://pub.dev/packages/envied) package for managing environment variables. The OpenAI API key is stored in an `.env` file and accessed through the `Env` class in `lib/env/env.dart`.

To set up your API key:

1. Create a `.env` file in the root directory.
2. Add your OpenAI API key with the variable name `OPEN_AI_API_KEY`. For example:
   ```
   OPEN_AI_API_KEY=your_api_key_here
   ```
3. Run the `build_runner` to generate the necessary code for `ENVied`.

### Acknowledgements

This app was developed based on the teachings of [Jaichang Park(Dreamwalker)](https://www.linkedin.com/in/park-jaichang-40359a154/) from [Fast Campus](https://fastcampus.co.kr/dev_online_dartflutter).
