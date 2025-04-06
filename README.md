# AI Vocab English Test

This project is a Jupyter Notebook-based application designed to help users practice English vocabulary using AI-generated questions. The system intelligently generates vocabulary tests based on the CEFR (Common European Framework of Reference) levels, providing multiple-choice questions for effective learning.

## Features

- 🔤 **Vocabulary Tests**: Automatically generates multiple-choice questions based on vocabulary level.
- 🧠 **AI-Powered Question Generation**: Uses intelligent logic to create distractors (wrong answers) for each question.
- 📝 **CEFR Level Filtering**: Customize questions based on A1 to C2 difficulty levels.
- 📊 **Performance Feedback**: Evaluates user responses and provides immediate feedback.

## Installation

1. Clone or download this repository.
2. Install required packages (recommended to use a virtual environment):

```bash
pip install -r requirements.txt
```

> If `requirements.txt` is not available, install commonly used packages manually:
```bash
pip install pandas numpy nltk
```

## Usage

1. Open the notebook:

```bash
jupyter notebook "AI vocab English test .ipynb"
```

2. Run the cells in order to:
   - Load and preprocess vocabulary data.
   - Generate multiple-choice questions.
   - Interact with the test interface.

## File Structure

- `AI vocab English test .ipynb` – Main notebook for vocabulary quiz generation.
- `vocab_data.csv` (not included) – Expected vocabulary dataset with columns like `word`, `definition`, `CEFR_level`, etc.

## Notes

- Ensure the vocabulary dataset is clean and follows the expected schema.
- You can customize difficulty, number of questions, or answer logic in the notebook cells.

## License

This project is licensed under the MIT License. Feel free to use and modify.

---

📧 For queries or suggestions, contact: mohmedessam166202@gmail.com
