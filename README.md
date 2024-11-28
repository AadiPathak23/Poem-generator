# Poem-generator
This project generates original, poem-like text inspired by Shakespeare’s writing style using an LSTM-based deep learning model. Trained on Shakespeare’s works, it mimics his vocabulary and tone. Users can adjust text length and creativity with provided parameters, and a pretrained model is included for quick use.
Features
Text Generation: Creates text resembling Shakespeare's style based on learned patterns.
Adjustable Creativity: Customize the randomness of outputs using a temperature parameter (e.g., structured vs. creative text).
Pretrained Model: Includes a ready-to-use pretrained LSTM model (textgenerator.keras) for generating text without additional training.
Getting Started
Prerequisites
Python 3.x
TensorFlow
NumPy
Install the required dependencies:

bash
Copy code
pip install tensorflow numpy
Running the Script
To generate text:

Clone the repository:
bash
Copy code
git clone <repository-url>
cd <repository-directory>
Run the script:
bash
Copy code
python generate_poem.py
Customizing Outputs
length: Sets the number of characters in the generated text.
temperature: Controls randomness:
Low values (e.g., 0.2) produce structured, predictable text.
High values (e.g., 1.0) create varied and creative text.
Example:

python
Copy code
print(generate_text(300, 0.6))
Examples
Generated Text (Temperature: 0.6)
css
Copy code
thy heart and hand, and bid him spare thee grace,
that thou dost bear thy reason and thy love,
and speak to those that dare to love thee most.
Project Files
generate_poem.py: Main script for generating text.
textgenerator.keras: Pretrained LSTM model.
.gitignore: Excludes unnecessary files like cache and environment files.
