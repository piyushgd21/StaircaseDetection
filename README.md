# Staircase Detection for Safe Mobility of Visually Impaired People
In a world where mobility is a crucial aspect of independence, individuals with visual impairments often face significant challenges navigating environments safely. This project aims to address one of these challenges by developing an advanced system for detecting staircases, a common obstacle that can pose serious risks.

## Objective
The primary objective of this project is to create a reliable, efficient, and user-friendly system that can accurately detect staircases and alert visually impaired individuals in real-time. By leveraging machine learning and computer vision techniques, this system aims to enhance the mobility and independence of its users.

## Key Features
- Real-Time Detection: Utilizes state-of-the-art algorithms to detect staircases in real-time.
- High Accuracy: Achieves an accuracy rate of up to 95.54% using the Random Forest classifier.
- User-Friendly Feedback: Provides immediate haptic and audio feedback to alert users of detected staircases.
- Multi-Classifier Approach: Compares the performance of various classifiers including KNN, Random Forest, - Logistic Regression, SVM, and Decision Tree to ensure optimal performance.

## Methodology
- Data Collection and Preprocessing:
- Collecting a comprehensive dataset of staircase images.
- Preprocessing the images using techniques like resizing, normalization, and augmentation to enhance model performance.
- Feature Extraction:
- Utilizing Scale-Invariant Feature Transform (SIFT) to extract significant features from the images.
- Applying Principal Component Analysis (PCA) to reduce dimensionality and improve computational efficiency.

## Model Training and Evaluation:
- Training multiple classifiers to identify the most effective model.
- Evaluating the models based on accuracy, precision, recall, and F1-score.

## Real-Time Implementation:
- Integrating the best-performing model into a real-time detection system.
- Developing a user interface that provides immediate feedback through haptic and audio signals.

## Results and Performance
The project has successfully demonstrated high accuracy in detecting staircases, with the Random Forest classifier achieving the highest accuracy of 95.54% using Decision Tree Classifier.

## Future Work
Extended Dataset: Expanding the dataset to include various types of staircases and environmental conditions.
Enhanced Algorithms: Exploring deep learning techniques to further improve detection accuracy.
User Testing: Conducting extensive user testing to gather feedback and make necessary improvements.
Integration with Wearable Devices: Developing wearable solutions that can seamlessly integrate with the detection system for more practical usage.
Conclusion
This project represents a significant step towards enhancing the safety and mobility of visually impaired individuals. By combining advanced machine learning techniques with real-time implementation, it provides a practical solution to a critical problem. The future enhancements aim to further improve the system's reliability and user experience, making it a valuable tool for visually impaired users worldwide.

## 📄 Research Paper
For more details on the methodology, implementation, and results, refer to our research paper:  
[🔗 Click here to read the full paper](https://pubs.aip.org/aip/acp/article-abstract/2754/1/070018/2909622/Staircase-detection-for-safe-mobility-of-visually)

## 📜 Citation
If you find this work useful, please cite our paper as follows:

Deshpande, Piyush, et al.  
*"Staircase Detection for Safe Mobility of Visually Impaired People."*  
*AIP Conference Proceedings, vol. 2908, 2023, p. 070018.*  
Available at: [🔗 pubs.aip.org](https://pubs.aip.org/aip/acp/article-abstract/2754/1/070018/2909622/Staircase-detection-for-safe-mobility-of-visually)  
DOI: [https://doi.org/10.1063/5.0161151](https://doi.org/10.1063/5.0161151)  
Accessed 14 Feb. 2025.  

### **📄 BibTeX Format**  
```bibtex
@article{deshpande2023staircase,
  author    = {Deshpande, Piyush and others},
  title     = {Staircase Detection for Safe Mobility of Visually Impaired People},
  journal   = {AIP Conference Proceedings},
  volume    = {2908},
  pages     = {070018},
  year      = {2023},
  url       = {https://pubs.aip.org/aip/acp/article-abstract/2754/1/070018/2909622/Staircase-detection-for-safe-mobility-of-visually},
  doi       = {10.1063/5.0161151}
}

