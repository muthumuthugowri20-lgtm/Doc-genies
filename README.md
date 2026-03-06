README FILE

# 📚 Doc-Genie v2.0

Doc-Genie is an AI-powered Python documentation generator that transforms raw function code into well-documented snippets using professional standards. 

## ✨ Features
- **Intelligent Analysis**: Uses AST (Abstract Syntax Tree) to recognize loops, conditions, and math operations.
- **Multiple Styles**: Supports both Google-style and NumPy-style docstrings.
- **Batch Processing**: Upload `.py` files directly to the interface.
- **Export Options**: Download your documentation history as a formatted PDF or a plain text file.
- **Social Sharing**: Generate instant share links for WhatsApp and Facebook.
- **Modern UI**: Built with a sleek, dark-themed Gradio interface.

## 🚀 How to Use
1. **Run the Script**: Execute the Python file to launch the Gradio web server.
2. **Input Code**: Paste your Python function into the code block or upload a `.py` file.
3. **Select Style**: Choose between 'Google' or 'NumPy' formatting.
4. **Generate**: Click "Generate Docstring" to see your code updated with a professional docstring.
5. **Export**: Use the controls on the right to download your session history as a PDF or TXT.

## 🛠️ Technology Stack
- **Gradio**: For the interactive web interface.
- **ReportLab**: For professional PDF generation.
- **AST (Python Standard Library)**: For deep code inspection and logic analysis.
- **Transformers**: Integrated support for IBM Granite models for local inference.
-
