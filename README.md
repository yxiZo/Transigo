# Transigo

## Introduction

**Universal Translation Project** is a universal translation tool that provides a simple and efficient API service for easy integration with various large models. The project supports two modes of operation:

- **Offline Mode**: Translates text using large models once and exports i18n files for later use.
- **Online Mode**: Directly calls a generic API for real-time translation by interacting with multiple translation models.

The project aims to simplify multilingual translation, offering flexibility and extensibility to meet a wide range of needs.

## Features

- **Universal API**: A unified interface for easy integration with various large language models.
- **Offline Translation**: Supports exporting translated texts to i18n format, ideal for offline use.
- **Online Translation**: Real-time translation with API calls for dynamic translations.
- **Multilingual Support**: Supports translations in multiple languages to meet global needs.
- **Flexible Extensibility**: Easily integrates with new translation models as needed.

## Tech Stack

- **Backend**: Node.js, Python (Flask/Django), or Java (Spring Boot)
- **Translation Models**: Integrates with various AI translation services (e.g., OpenAI, Google Translate API, AWS Bedrock)
- **Database**: Stores translation results and i18n texts (e.g., MySQL, MongoDB)
- **API**: RESTful API or GraphQL

## Installation & Setup

### Clone the repository

```bash
git clone https://github.com/yourusername/universal-translation.git
cd universal-translation
