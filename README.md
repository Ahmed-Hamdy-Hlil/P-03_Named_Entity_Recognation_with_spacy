# Named Entity Recognition with spaCy and displaCy

## Description
This project demonstrates the use of Named Entity Recognition (NER) through [spacy](https://spacy.io/), a powerful NLP library, and [displacy](https://spacy.io/usage/visualizers), a built-in visualization tool for rendering NER. The project allows users to input text through a web interface created with [Streamlit](https://streamlit.io/) and visualizes the detected entities in the text.

## Features
- **Named Entity Recognition:** Identifies key entities such as names, locations, dates, etc., from the text using spaCy's pre-trained models.
- **Entity Visualization:** Displays NER results with displaCy, making it easy to see what entities were recognized.
- **Interactive Web Interface:** Built with Streamlit for easy user interaction.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ner-with-spacy-displacy.git
    cd ner-with-spacy-displacy
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit application:
    ```bash
    streamlit run _Project_3_Named_Entity_Recognation_with_spacy_and_displacy.ipynb
    ```

## Dependencies
- [spaCy](https://spacy.io/)
- [Streamlit](https://streamlit.io/)
- [displaCy](https://spacy.io/usage/visualizers)
- Python 3.x

## Usage
1. Start the application by running the Streamlit command.
2. Enter a block of text into the input field.
3. View the named entities highlighted in different categories such as people, organizations, locations, and more using displaCy’s interactive visualizations.

## Customization
- You can customize the spaCy model by adding your own training data for specific domains.
- The project is modular, allowing easy extensions such as integrating with advanced models or additional languages.

## Contributing
Contributions are welcome! Please open issues or submit pull requests if you want to help improve this project.
