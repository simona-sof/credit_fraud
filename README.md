# Credit Card Fraud Detection

This project employs a voting classifier composed of both supervised and semi-supervised models to detect credit card fraud with high accuracy. The final tuned model includes:

- **Supervised Models:**
  - Random Forest Classifier
  - Gaussian Naive Bayes
  - Histogram-based Gradient Boosting Classification Tree (HistGB)

- **Semi-Supervised Models:**
  - Label Spreading
  - Label Propagation

### Performance

The final model achieves:
- **Accuracy:** 0.96
- **Precision:** 0.96
- **Recall:** 0.96

It results in only 4 false positives and 4 false negatives.

## Installation

To run this project, you need to have Python installed along with several libraries. You can install the required libraries using:

```bash
pip install -r requirements.txt

## Data

1. Download the dataset from [this URL](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
2. Create a folder named `data` in the project directory.
3. Place the downloaded dataset into the `data` folder.

```bash
mkdir data
# Move the downloaded file to the data folder
mv path/to/your/downloaded/file data/

4. Run the project in the notebook


## Dataset Citation

1. **Andrea Dal Pozzolo, Olivier Caelen, Reid A. Johnson and Gianluca Bontempi.** "Calibrating Probability with Undersampling for Unbalanced Classification." *Symposium on Computational Intelligence and Data Mining (CIDM), IEEE, 2015.*

2. **Dal Pozzolo, Andrea; Caelen, Olivier; Le Borgne, Yann-Ael; Waterschoot, Serge; Bontempi, Gianluca.** "Learned lessons in credit card fraud detection from a practitioner perspective." *Expert Systems with Applications, 41(10), 4915-4928, 2014, Pergamon.*

3. **Dal Pozzolo, Andrea; Boracchi, Giacomo; Caelen, Olivier; Alippi, Cesare; Bontempi, Gianluca.** "Credit card fraud detection: a realistic modeling and a novel learning strategy." *IEEE Transactions on Neural Networks and Learning Systems, 29(8), 3784-3797, 2018, IEEE.*

4. **Dal Pozzolo, Andrea.** "Adaptive Machine learning for credit card fraud detection." *ULB MLG PhD thesis (supervised by G. Bontempi).*

5. **Carcillo, Fabrizio; Dal Pozzolo, Andrea; Le Borgne, Yann-Aël; Caelen, Olivier; Mazzer, Yannis; Bontempi, Gianluca.** "Scarff: a scalable framework for streaming credit card fraud detection with Spark." *Information Fusion, 41, 182-194, 2018, Elsevier.*

6. **Carcillo, Fabrizio; Le Borgne, Yann-Aël; Caelen, Olivier; Bontempi, Gianluca.** "Streaming active learning strategies for real-life credit card fraud detection: assessment and visualization." *International Journal of Data Science and Analytics, 5(4), 285-300, 2018, Springer International Publishing.*

7. **Bertrand Lebichot, Yann-Aël Le Borgne, Liyun He, Frederic Oblé, Gianluca Bontempi.** "Deep-Learning Domain Adaptation Techniques for Credit Cards Fraud Detection." *INNSBDDL 2019: Recent Advances in Big Data

## License
This project is licensed under the Database Contents License (DbCL) v1.0.
