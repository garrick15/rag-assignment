# RAG Assignment

A JavaFX desktop application that implements a Retrieval Augmented Generation (RAG) chatbot powered by OpenAI.

## Features

- **Chat Interface** - Interactive chat UI with conversation history
- **Knowledge Base Management** - Import and manage PDF documents as context
- **RAG-powered Responses** - Uses document embeddings to provide context-aware answers
- **Session Management** - Create, edit, and manage multiple chat sessions
- **Dark/Light Theme** - Toggle between dark and light modes
- **Persistent Storage** - SQLite database for storing sessions and chat history

## Tech Stack

- **Java 25** with JavaFX 21
- **LangChain4j** - LLM integration framework
- **OpenAI API** - GPT models for chat and text-embedding-3-small for embeddings
- **Apache PDFBox** - PDF document parsing
- **SQLite** - Local database storage
- **Log4j2** - Logging

## Prerequisites

- Java 25 or higher
- Maven 3.6+
- OpenAI API key

## Setup

1. Download the repository. This assignment is submitted as a zip file, therefore no git is involved.

2. Create a `.env` file in the project root and add your OpenAI API key:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```

## Running the Application

### Option 1: Run with Maven

```bash
mvn clean javafx:run
```

### Option 2: Build from Source

To build the standalone JAR yourself:

```bash
mvn clean package
```

This will generate `target/rag-1.0-SNAPSHOT.jar` which can be run with `java -jar`.

## Project Structure

Refer to the Part A report.

## Usage

Refer to the Part B report.

## License

This project is for educational purposes.
