# Project Overview

This project implements a hybrid Convolutional Neural Network (CNN) and Decision Tree (DT) model for image classification, combining the robust feature extraction of CNNs with the interpretability of DTs. The project demonstrates how to balance model accuracy with transparency, making the model suitable for applications requiring explainable AI. Users can explore the model architecture, train and evaluate the hybrid model, and visualize decision pathways to gain insights into how predictions are made.

The following instructions outline the setup process, including installing dependencies and configuring Graphviz (for Windows users), to ensure smooth execution of the project.

---

# Project Setup

## Step 1: Install Requirements
To install all required libraries, run:
```bash
pip install -r requirements.txt
```
## Step 2: Graphviz Setup (Windows Users)

For Windows users, Graphviz may require additional setup:

### 1. Install Graphviz
Download the Graphviz installer from the [Graphviz download page](https://graphviz.gitlab.io/download/).

### 2. Set the Graphviz Path
After installation, add Graphviz's `bin` directory to your system's PATH environment variable. This allows `pydotplus` to locate Graphviz.

- Open **Environment Variables** settings.
- Edit the `PATH` variable to include the path to your Graphviz `bin` directory, usually:
  ```plaintext
  C:\Program Files\Graphviz\bin
   ```
