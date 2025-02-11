# Project Title

A brief description of your project.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Usage](#usage)

## Prerequisites

Before you begin, ensure you have the following installed:

- [Python 3.x](https://www.python.org/downloads/)
- [pip](https://pip.pypa.io/en/stable/installation/)

## Setup

Follow these steps to set up the project on your local machine.

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/dalmergeo/llm-demo.git
cd llm-demo
```

### 2. Create a Virtual Environment

Create a virtual environment in a directory named `.venv`:

```bash
python -m venv .venv
```

(NOTE: If you are using a different version of Python, replace `python` with `python3`.)

### 3. Activate the Virtual Environment

Activate the virtual environment:

```bash
source .venv/bin/activate
```

### 4. Install the Dependencies

Install the project dependencies:

```bash
pip install -r requirements.txt
```

### 5. Set up `.env` File

Create a `.env` file in the project root directory and add the following environment variables:

```bash
OPENAI_API_KEY=your_openai_api_key_here
MERGE_API_KEY=your_merge_api_key_here
MERGE_ACCOUNT_TOKEN=your_merge_account_token_here
```

## Usage

To run the project, execute the following command:

```bash
jupyter notebook
```

This will open a Jupyter Notebook in your browser. Open the `llm_demo.ipynb` notebook and run the cells to see the project in action.