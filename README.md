# Text Content Moderation API

A robust API for real-time text content moderation, ensuring a safe and positive user experience. Easily monitor and rate text for hate speech, profanity, and sentiment using natural language processing (NLP). The API is live at [Text Content Moderation](https://text-content-moderation.onrender.com).

## Overview

The Text Content Moderation API is designed to monitor, assess, and rate text content in real-time. It leverages advanced NLP techniques to identify and categorize content, making it ideal for maintaining a clean and respectful online environment.

## Getting Started

To set up and use the Text Content Moderation API, follow these steps:

1. Clone the repository to your local machine:

   ```shell
   git clone https://github.com/mjavason/Text-Content-Moderation-API.git
   ```

2. Navigate to the project directory:

   ```shell
   cd Text-Content-Moderation-API
   ```

3. Install the required dependencies:

   ```shell
   npm install
   ```

4. Set up the environment variables by creating a `.env` file in the root directory. Replace the placeholders with your actual values. Refer to the "Environment Variables" section below for details.

5. Start the server:

   ```shell
   npm start
   ```

The API will be accessible at `http://localhost:5000` by default.

## Features

- **Text Content Analysis**: Monitor and rate text content for hate speech, profanity, and sentiment.
  
- **Real-Time Moderation**: Analyze text in real-time, providing instant feedback and categorization.

## Environment Variables

Before running the API, ensure you have set up the following environment variables in your `.env` file:

```env
API_DOCUMENTATION_URL=doc.xxx.com
APP_NAME = TemplateApp
MAIL_ADDRESS=xxxx@mail.com
MAIL_PASSWORD=xxxx
SITE_LINK=xxxx
USERNAME =  user@mail.com
```

Replace the placeholders with your actual secret keys, URLs, and credentials.

## Documentation

For detailed documentation on how to use the Text Content Moderation API and its endpoints, refer to the [API Documentation](https://documenter.getpostman.com/view/29278179/2s9YJgVMFA).

## Contributing

Contributions to the Text Content Moderation API are highly encouraged! If you'd like to contribute:

1. Fork the project on GitHub.

2. Create a new branch for your changes.

3. Implement your improvements or additions.

4. Rigorously test your changes.

5. Submit a pull request with a clear description of your modifications.

Your contributions will play a crucial role in enhancing the functionality and effectiveness of this API, ensuring a safer online space for all users.
