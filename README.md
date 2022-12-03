# LunarHacks22 IngredientSafe project

Packaged food, medication, make-up, what do they have in common? Tiny but important ingredient labels. We created an interactive scanner to keep the aging and visually impaired safe from allergens.

**About the project**

Ingredientsafe is an ingredient scanner that scans for a user’s allergies or other dietary restrictions. The webpage was coded in HTML and CSS while the back end and logic portion was coded in Python. 

**Backend Code**

main.py: Python script that scans the given ingredient list image and compares user input from the website to the text produced from image-to-text. Returns message notifying user if product is safe to consume or not.
- note: to run properly, user will need to have cv2 and pytesseract modules (cmd line: pip install opencv-python, pip install pytesseract, install-pkg tesseract-ocr)

ingredients.jpg: Example image for an ingredient list

**Frontend Code**

homepage.html: HTML file for homepage

homepage.css: CSS file for homepage styling

homepage.js: JS file for homepage

results.html: HTML file for results page

results.css: CSS file for results page styling

background.png: Background image for IngredientSafe website
