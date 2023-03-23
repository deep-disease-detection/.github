# 🙋‍♀️ What is Deep Disease Detection (DDD) ?
Deep Disease Detection is a decision making tool for medical laboratories. It leverages several deep learning architectures (CNNs, YOLO) to enable scientist to classify and detect viruses on TEM microscope images.
&nbsp;

The project was started in a data science bootcamp and is still work in progress. It is based on the work of Damian J. Matuszewski and Ida-Maria Sintorn, TEM virus images: Benchmark dataset and deep learning classification.


# ⚙️ Code and Repositories

The project code is organized in several repositories:

- <a href="https://github.com/deep-disease-detection/ddd-ai"> ddd-ai </a>: Core package. Includes TEM microscope image preprocessing and augmentation, CNN models initialization, training and evaluation code as well as our API
- <a href="https://github.com/deep-disease-detection/ddd-object-detectionV8"> ddd-object-detectionV8 </a>: Object detection model leveraging <a href="https://docs.ultralytics.com/"> YOLOv8 from ultralytics </a>
- <a href="https://github.com/deep-disease-detection/ddd-cloud"> ddd-cloud </a>: Includes our Streamlit dashboard code as well as code used on Google Cloud to receive data from the microscope and process it using Cloud Functions
- <a href="https://github.com/deep-disease-detection/ddd-edge"> ddd-edge </a>: Edge code to send images from a computer and/or a microscope to the our Google Cloud Project using Pub/Sub




# 🌈 Contribution guidelines
Please contact one of the organization members if you want to contribute or if you have any other questions!
- [Laura](https://github.com/laudesire)
- [Walid](https://github.com/walid213)
- [Youssef](https://github.com/youssyml)
- [Sabrina](https://github.com/sdacelo)


# 👩‍💻 Useful resources
- [Scientific paper](https://www.sciencedirect.com/science/article/pii/S0169260721003928?via%3Dihub#bib0024)
- [Paper code](https://data.mendeley.com/datasets/kxsvzhcfgs)
- [Paper dataset](https://data.mendeley.com/datasets/kxsvzhcfgs/2)
