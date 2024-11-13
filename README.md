# VSCode Configuration for Continue with Ollama

This repository contains the configuration for integrating Continue in Visual Studio Code (VSCode) with the Ollama models. The configuration enables advanced code completion, error detection, and unit test generation, powered by Ollama's AI models.

## Configuration Overview

The configuration consists of several key parts:

- **Telemetry**: Anonymous telemetry is disabled (`allowAnonymousTelemetry: false`).
- **Models**: A list of models available for use in VSCode.
- **Completion Options**: Configuration for how the AI will generate code completions.
- **Custom Commands**: Custom commands for specific use cases like unit testing and error checking.
- **Context Providers**: Various context providers that enhance the AI's understanding of the current coding environment.
- **Embeddings Provider**: Model for generating text embeddings for better context comprehension.
- **Tab Autocomplete Model**: Model used for autocompletion when the Tab key is pressed.

## Configuration Details

### Models

The `models` section defines the settings for the Ollama model that will be used for code completion:

```json
{
  "title": "Ollama",
  "provider": "ollama",
  "model": "AUTODETECT",
  "apiBase": "http://34.34.152.157:11434"
}
