# Computer Vision – Age Estimation from Facial Images

---

## Project Overview

This project explored the application of computer vision techniques to estimate a person’s age from facial images. The primary goal was to develop a model capable of determining whether an individual is of legal age to purchase alcohol, using a large dataset of labeled face photographs.

---

## Project Highlights

- Loaded and processed a dataset of over 7,000 facial images with real age labels
- Performed exploratory data analysis to understand age distribution and class balance
- Utilized data generators to efficiently handle large image datasets
- Built and trained a deep learning model using transfer learning (ResNet50 backbone)
- Evaluated model performance using Mean Absolute Error (MAE) on a held-out test set

---

## Outcome

The best model achieved a test MAE below the project threshold, demonstrating strong performance in age estimation from images. The project provided valuable insights into the challenges and potential of computer vision for real-world tasks such as age verification, highlighting the effectiveness of transfer learning and the importance of robust data preprocessing.

---

## Business Impact

By automating age estimation, businesses can streamline compliance with age-restricted product regulations, reduce manual verification costs, and enhance customer experience. The developed solution lays the groundwork for integrating computer vision into real-time age verification systems.

---

## Resources

- [Project Notebook](s15_cv.ipynb)
- [Model Training Script](run_model_on_gpu.py)

---

[⬅️ Back to Directory](../../README.md)