# Medical Web Application for Disease Detection
The disease detection app provides users with tools and resources to monitor their health, receive personalized recommendations, and access medical assistance when needed. Users can input symptoms, track health metrics, and receive potential diagnoses or recommendations for further evaluation. The app offers educational content about various diseases, symptoms, and risk factors, empowering users to make informed decisions about their health. While the app serves as a complementary tool to traditional healthcare services, it is not a substitute for professional medical advice. Users are encouraged to seek timely medical evaluation and treatment when necessary, especially for serious or life-threatening conditions. Overall, the app aims to facilitate early detection, empower users to take control of their health, and improve healthcare accessibility and outcomes.

## Motivation
### 1. Importance of Time in Healthcare:
 * Timely diagnosis and treatment are paramount in healthcare, where every minute can impact patient outcomes.
 * Delays in diagnosis may result in missed opportunities for intervention, leading to adverse health consequences for patients.
### 2. Challenges Faced by Radiologists:
 * Radiologists often have to interpret numerous imaging studies each day, with limited time available for each case.
 * High volume of reports to review can lead to challenges in providing timely results, potentially delaying patient care.
### 3. Impact on Patients:
 * Prolonged waiting times for diagnostic tests and results contribute to patient anxiety and uncertainty about their health.
 * Faster turnaround times for diagnostic evaluations can alleviate patient anxiety and improve the overall patient experience.
### 4. Project Objectives:
 * Our project aims to streamline the diagnostic process, enabling healthcare professionals to deliver prompt and effective treatment.
 * By automating certain aspects of the diagnostic workflow, we aim to expedite the delivery of critical findings, particularly in radiology.
### 5. Empowering Patients:
  * Rapid and accurate diagnoses empower patients to take proactive steps towards managing their health.
  * Access to timely interventions can lead to better health outcomes and improved quality of life for patients.

## Technologies Used
#### Frontend: HTML5, CSS3, JavaScript, Bootstrap 4.
               
#### Backend: Flask
#### Machine Learning and Data Processing:
 1. TensorFlow and Keras: For building and deploying deep learning models.
 2. Scikit-learn: For classical machine learning algorithms.
 3. XGBoost: For heart disease prediction.
 4. OpenCV: For image processing tasks.

## Machine Learning Models
* #### Brain Tumor Detection:
   * Feature Extraction: VGG-16 pretrained model.
   * Classification: Custom CNN model.
   * Accuracy: 85%
* #### Alzheimer's Detection:
   * Model: Custom CNN.
   * Accuracy: 75%
* #### Pneumonia Detection:
   * Model: Custom CNN.
   * Accuracy: 84.19%
* #### COVID-19 Detection:
   * Model: Custom CNN.
   * Accuracy: 94%
* #### Breast Cancer Detection:
   * Model: Random Forest Classifier.
   * Accuracy: 91%
* #### Heart Disease Prediction:
   * Model: XGBoost.
   * Accuracy: 86.99%
* #### Diabetes Prediction:
   * Model: Random Forest Classifier.
   * Accuracy: 66.8%

## Installation
To set up the project locally, follow these steps:

### 1. Clone the Repository:
```
git clone https://github.com/radhika3131/DiagnoNow
cd DiagnoNow

```
### 2. Create a Virtual Environment:
```
python -m venv virtualEnvName
.\virtualEnvName\Scripts\activate

```
### 3. Install the Required Packages:
```
pip install -r requirements.txt
```
### 4. Run the Application:
```
flask run
```
### 5. Access the Web Application:
Open your web browser and navigate to  'http://127.0.0.1:5000'

## Usage
 * Home Page: From the home page, users can navigate to the specific disease detection sections.
 * Upload Image or Enter Data: Users can upload the relevant medical images (e.g., X-rays, MRIs) or enter health metrics.
 * Get Results: The application processes the input and provides diagnostic results, indicating the likelihood of the condition.

#### Homepage
![Screenshot (118)](https://github.com/vivekrajput18/Health-Detector-/assets/74731093/b714f234-9a07-4447-ae50-7cfd5d88c217)

#### One of the detection result
![Screenshot (119)](https://github.com/vivekrajput18/Health-Detector-/assets/74731093/c88f6cc9-998d-4496-9a0a-4b415e607b13)


## Acknowledgments
This project was made possible through the collaboration of dedicated team members and the guidance of knowledgeable mentors.
### Team members:
 * Radhika Ramsen
 * Purvakshi
 * Vivek Rajput
### Advisors
 * Prakiriti Raghuvanshi
 * Anushree Negi
   
We extend our gratitude to our advisors for their invaluable insights and support.

## Future Scope
 * Enhance the user interface for a better user experience.
 * Expand the application to support additional diseases.
 * Enhanced data security and sharing
 * Implemented as a mobile application
 * Improve model accuracy and reduce false positives/negatives.
   



