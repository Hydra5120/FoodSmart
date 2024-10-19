# Welcome to Foodsmart

Discover an interactive way to find meal suggestions based on your preferences, needs, and the ingredients you already have. Skip the hassle of expensive grocery runs and overwhelming recipe searches. With **Foodsmart**, you get:

- **Clear, simplified instructions** with precise measurements
- **User-friendly software** for a seamless experience

## How It Works

We offer **three convenient ways** to input your ingredients:

1. **Photo Detection**  
   Upload an image of your fridge, and our program will identify up to five ingredients from the photo.
   
2. **Manual Input**  
   Fill out a simple form with the ingredients you have on hand.
   
3. **Paragraph Input**  
   Paste a block of text, and we’ll detect ingredients by analyzing key terms.

---

### The Results

Once your ingredients are processed, **Foodsmart** will provide a curated list of meal options, complete with:

- **Recipes**
- **Calorie counts**
- **Serving sizes**



## Technology Stack

Developed the frontend using **HTML**, **CSS**, and **JavaScript**, while the backend was built with **Flask** and **Python**. The app delivers live recipe data via the **Edamam Recipes API** and is hosted on an **nginx live server** running on an **Azure Virtual Machine** with a custom domain.

### Machine Learning


- Trained a **Clarifai multiclass visual classifier model** on a custom dataset.
- Utilized **Yet Another Keyword Extractor (YAKE)** to perform natural language processing, enabling us to extract keywords and predict sentiment from text.
