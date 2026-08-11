# 🌸 Iris Flower Classification Using Java

## 📌 Overview

Iris Flower Classification is a machine-learning project developed in Java that predicts the species of an iris flower based on its sepal and petal measurements.

The system uses the **K-Nearest Neighbors (KNN)** classification algorithm.

The three possible flower species are:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

## 🎯 Objective

The main objective of this project is to demonstrate how machine-learning classification can be implemented using Java.

The system accepts four measurements:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

It then compares the input with known training samples and predicts the most likely iris species.

## 🛠️ Technologies Used

* Java
* K-Nearest Neighbors (KNN)
* Object-Oriented Programming
* Euclidean Distance
* Iris Dataset
* GitHub

## 🧠 Algorithm

The project uses the K-Nearest Neighbors algorithm.

For a new flower:

1. Calculate the distance between the new flower and training samples.
2. Sort the samples according to distance.
3. Select the nearest K samples.
4. Count the species of the selected samples.
5. Select the species with the highest number of votes.
6. Display the predicted species.

## 📐 Distance Formula

```text
Distance = √((x1-y1)² + (x2-y2)² + (x3-y3)² + (x4-y4)²)
```

## 📂 Project Structure

```text
iris-flower-classification/
│
├── src/
│   └── IrisClassification.java
│
├── data/
│   └── iris.csv
│
├── README.md
│
└── .gitignore
```

## ▶️ How to Run

### Step 1: Install Java

Make sure Java JDK is installed.

Check the installation:

```bash
java --version
```

### Step 2: Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 3: Open the project

```bash
cd iris-flower-classification
```

### Step 4: Compile

```bash
javac src/IrisClassification.java
```

### Step 5: Run

```bash
java -cp src IrisClassification
```

## 🧪 Sample Input

```text
Sepal Length : 5.9
Sepal Width  : 3.0
Petal Length : 5.1
Petal Width  : 1.8
```

## 📊 Sample Output

```text
====================================
     IRIS FLOWER CLASSIFICATION
====================================

Input Flower Measurements:
Sepal Length : 5.9
Sepal Width  : 3.0
Petal Length : 5.1
Petal Width  : 1.8

Algorithm : K-Nearest Neighbors
K Value   : 3

Predicted Species:
>>> Iris Virginica

Classification completed successfully!
====================================
```

## 🌟 Features

* Flower species classification
* KNN-based prediction
* Euclidean distance calculation
* Simple Java implementation
* Easy-to-understand code
* Console-based simulation

## 💡 Applications

* Flower species identification
* Machine-learning education
* Pattern recognition
* Data classification
* Academic demonstrations
* Botanical data analysis

## ⚠️ Limitations

* Small demonstration dataset
* Console-based interface
* No automatic dataset loading
* No graphical visualization
* No formal train/test accuracy evaluation

## 🚀 Future Improvements

* Add the complete Iris dataset
* Load data automatically from CSV
* Add train/test splitting
* Calculate classification accuracy
* Add JavaFX/Swing GUI
* Add data visualization
* Compare multiple ML algorithms
* Create a web-based interface

## 👩‍💻 Author

Developed as a Java machine-learning project for educational purposes.

## 📄 License

This project is intended for educational and academic use.
