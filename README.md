# Calculator MCP Server

A simple Model Context Protocol (MCP) server that provides basic calculator operations (addition, subtraction, multiplication, division, and power) using FastMCP.

## Setup and Installation

### 1. Create a Virtual Environment
If you haven't already, create a Python virtual environment:
```bash
python3 -m venv .venv
```

### 2. Activate the Virtual Environment
Activate the environment before running the server or installing dependencies:

* **macOS and Linux:**
  ```bash
  source .venv/bin/activate
  ```
* **Windows (Command Prompt):**
  ```cmd
  .venv\Scripts\activate.bat
  ```
* **Windows (PowerShell):**
  ```powershell
  .venv\Scripts\Activate.ps1
  ```

### 3. Install Dependencies
Install the required Python packages:
```bash
pip install -r requirements.txt
```

---

## Running the Server

To start the Calculator MCP server, run:
```bash
python server.py
```

This starts the server using the HTTP/SSE transport on `http://0.0.0.0:8000/mcp`.

---

## Deactivating the Virtual Environment

To exit the virtual environment when you are done, simply run:
```bash
deactivate
```
