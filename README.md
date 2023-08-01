# Hypertension Detector

## Project Description

High blood pressure, also known as hypertension, usually develops over time and can be caused by unhealthy lifestyle choices, such as lack of regular physical activity. Certain health conditions, such as diabetes and obesity, can also increase the risk of developing high blood pressure.

The main objective of the Hypertension Detector project is to control hypertension and prevent the occurrence of cardiovascular diseases due to sustained high blood pressure, thereby reducing mortality.

## GUI Framework

The GUI for this project is built using Django and Bootstrap, providing a user-friendly interface for hypertension detection.

## Languages Used

- Python: The backend logic and machine learning algorithms are implemented using Python.
- HTML/CSS: The frontend GUI is developed using HTML and CSS for styling.
- JavaScript: It is used to add interactivity to the web application.

## Implemented Libraries

The following libraries are used in the project:

- Pandas: Used for data manipulation and analysis.
- Sklearn (Scikit-learn): Utilized for implementing the machine learning algorithm.

## Algorithm

The Hypertension Detector project uses the Random Forest algorithm as a supervised machine learning algorithm. Random Forest combines the output of multiple decision trees to reach a single result. Its ease of use and flexibility make it suitable for both classification and regression problems.

## Performance Analysis

"We tested five ML algorithms, exploiting different balancing techniques. Moreover, we computed the performance of the medical protocol currently adopted in the screening programs.

Results show that a gain of sensitivity reflects in a loss of specificity, bringing to a scenario where there is not an algorithm and a configuration which properly outperforms against the others.

However, Random Forest provides interesting performances (0.818 sensitivity - 0.629 specificity) compared with medical protocols (0.906 sensitivity - 0.230 specificity)."

## Conclusion

The machine learning models implemented in this project performed well to predict hypertension and its associated factors. When employed on an open-source platform, these models are scalable to millions of people and might help individuals self-screen for hypertension at an early stage.

Hypertension is a critical disorder, especially in aged people, and is associated with a higher risk of cardiovascular morbidity and mortality. Reducing blood pressure values can decrease the risk of cardiac death as well as neurological, metabolic, and musculoskeletal system sequelae in aged people.

## Installation and Usage

1. Clone the repository:

```bash
git clone https://github.com/iOMJaiswal/HypertensionDetectorML.git
```

2. Change into the project directory:

```bash
cd SmartHomeForElderPeople
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Start the development server:

```bash
python manage.py runserver
```

5. Access the web-app locally:

Open your web browser and go to `http://localhost:8000/`
