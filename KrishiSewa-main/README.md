# Krishi Sewa 🌾🚜

Welcome to **Krishi Sewa**, your go-to platform for essential agricultural support and intelligent crop recommendations!

## About Krishi Sewa
**Krishi Sewa** is a comprehensive platform designed to empower farmers by providing them with valuable agricultural insights and recommendations. At the heart of Krishi Sewa is an advanced crop recommendation model that helps farmers make informed decisions about which crops to cultivate. Our model takes into account a variety of factors, including soil types, climate conditions, and historical data, to provide personalized recommendations that maximize yield and profitability.

## Getting Started
To set up and run Krishi Sewa on your local machine, follow these simple steps:

1. Clone or download all the files from this repository.
2. Install the required dependencies listed in the `requirements.txt` file.
3. Run the `run.py` file in your preferred IDE.
4. Open the local host address provided in your terminal to access the fully functional website.

## Features
- **Crop Recommendation:** Leverage our sophisticated crop recommendation model to choose the best crops for your land based on data-driven insights.
- **User-Friendly Interface:** Our platform is built with simplicity in mind, allowing farmers to easily input data and receive personalized crop recommendations.
- **Data-Driven Insights:** Get insights powered by data analysis, including soil conditions, climate data, and historical crop performance.
- **Agricultural News:** Stay up to date with the latest trends and developments in agriculture through our curated news section.

## Directory Structure
- **app/**: Core Flask application files.
- **data/**: Datasets used for training and analysis.
- **static/**: Static files including images, CSS, and JavaScript.
- **best_model.pkl**: Pre-trained crop recommendation model saved as a pickle file.
- **standscaler.pkl**: Pickle file for the standard scaler used in model preprocessing.
- **minmaxscaler.pkl**: Pickle file for the min-max scaler used in model preprocessing.
- **CropRecommendationSystem.ipynb**: Jupyter notebook containing the source code for the crop recommendation model.
- **run.py**: Python script for running the Flask application.
- **result.html**: HTML template for displaying the crop recommendation results.
- **requirements.txt**: A text file listing all dependencies needed to run the application.

## Installation Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-repo/KrishiSewa.git
   cd KrishiSewa
   ```

2. **Create a virtual environment and activate it:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**
   ```bash
   python run.py
   ```

5. **Access the application:**
   - Open your browser and go to the local host address provided in the terminal (e.g., `http://127.0.0.1:5000`).

## Contributing
We welcome contributions from the community to make **Krishi Sewa** even more beneficial for farmers. Whether it's bug fixes, feature enhancements, or new ideas, your contributions are valued. Feel free to open an issue or submit a pull request to help improve the platform.

## Contact Us
Have any questions, suggestions, or feedback? We'd love to hear from you! Reach out to us at [Contact us](mailto:rahulvinodsharma21@gmail.com).

---

Thank you for choosing **Krishi Sewa**—empowering farmers, one crop at a time. 🌱🌟
