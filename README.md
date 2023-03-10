# **Machine learning Classifiers to Classify Noise Class**
This work investigates the suitability of different machine learning (ML) classifiers to classify the noise class accurately. The noise-classifier is one of the building blocks of the context-aware speech quality model for measuring and monitoring real-time speech quality. To this line, this work first prepares the dataset in which the speech enhancement algorithms are used in conjunction with an objective speech quality model (P.563) to estimate mean opinion score (MOS) of the noisy and the enhanced speech samples in order to train different ML classifiers for classifying the noise class (i.e., noise type and SNR). 7 different classifiers namely; XGBoost, Random Forest (RF), Decision Tree (DT), Logistic Regression, Support Vector Machine (SVM), K-nearest Neighbors (KNN), and Linear SVC (Lin. SVC) are used for classifying the noise class accurately. Results demonstrate that a Decision Tree (DT) classifier has better classification accuracy for the different noise classes tested. Note that
the MOS describes speech quality on a scale from 1 (bad) to 5 (excellent).

# **Requirements:**
* NOIZEUS Speech Corpus (Publicly available)
* Machine Learning Classifiers (XGBoost, Random Forest (RF), Decision Tree (DT), Logistic Regression, 
* Support Vector Machine (SVM), K-nearest Neighbors (KNN), and Linear SVC (Lin. SVC)
* TensorFlow
* Python

## **License**
* The project is licensed under the GNU General Public License v3.0.
* You may obtain a copy of the License at https://www.gnu.org/licenses/gpl-3.0.en.html

# **Citing Work**
* Rahul Jaiswal, Andrew Hines, Towards a Non-Intrusive Context-Aware Speech Quality Model,
31st IEEE Irish Signals and Systems Conference, pp. 219-223, 2020. https://ieeexplore.ieee.org/document/9180171


