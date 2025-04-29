# Stock Report Analysis with AI

This project reads stock report PDFs, provides key insights and analysis, and determines whether to buy or sell the stock using AI-powered insights.

## Features
- Reads and analyses stock report PDFs
- Extracts key insights and trends
- Provides a **Buy** or **Sell** recommendation
- Uses OpenAI API for advanced analysis

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/Rakesh-v27/AI_Stock_report_analysis.git
```

### 2. Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Set Up OpenAI API Key
To use this project, you need an OpenAI API key.

1. Create an OpenAI account and get your API key from [OpenAI's website](https://platform.openai.com/signup/).
2. Create a `.env` file in the root directory of the project.
3. Add the following line to the `.env` file:
   ```
   OPENAI_API_KEY="your-api-key-here"
   ```

### 5. Run the Notebook
Open Jupyter Notebook or Google Colab and run the notebook file.

## Notes
- The `.env` file **should not** be shared publicly as it contains sensitive information.
- The `venv/` and `.env` files are ignored using `.gitignore` to prevent accidental commits.

