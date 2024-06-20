# IoT-Edu-ML-Stream-Tool

A GUI tool integrating IoT data generation, real time big data platforms and Machine learning.

IoT-Edu-ML-Stream-Tool is an educational tool designed to emulate IoT environments, generate realistic sensor data, handle hardware-generated IoT data, and integrate with big data platforms for machine learning and data analysis.

---

## Features

- User-Friendly interface
- Real or emulated network
- Realistic data generation
- Continuous data monitoring
- Seamless integration with Big Data platforms
- Machine learning model deployment
- Scalability
- Customizability and extendibility

---

## Development Environment
The entire tool was designed using Visual Studio Code and supports any Python platform.

---

## Getting Started with IoT-Edu-ML-Stream Tool

### Step 1: Access the Code

Download the folder containin the files from the following OneDrive link:

[Access Code on OneDrive](https://alumniuaeuac-my.sharepoint.com/:f:/r/personal/nandanaj_uaeu_ac_ae/Documents/IoT-Edu-ML-Stream?csf=1&web=1&e=ZowPbV)

## IoT-Edu-ML-Stream

This folder contains essential files and scripts for the IoT-Edu-ML-Stream project. Below is a description of the contents within the 'IoT-Edu-ML-Stream' folder located in the above OneDrive link:

### Folder Contents:

- **'init.py'**: Initialization script for the project.
- **'1.csv'**: Sample CSV data file.
- **Kafka Files**:
  - 'producer.py': Script to produce messages to Kafka.
  - 'consumer.py': Script to consume messages from Kafka.
  - 'shared_kafka_topic_txt': Text file containing Kafka topic information.
  - 'stream.py': Script for streaming data.
  - 'kafka.py': Kafka main file.
- **Data Generation Files**:
  - 'data generation.py': Script for generating IoT data.
  - 'trained_rf_model.pkl': Pre-trained model weights.
- **'confi.yaml'**: Configuration file.
- **'utils.py'**: Utility functions used across the project.
- Also the images used in the GUI

### Step 2: Install Required Python Packages
### Prerequisites

Ensure you have the following installed:

- **Python 3.10.12**: [Download Python](https://www.python.org/downloads/)
  - After downloading, install 'pip' (Python's package installer) if it's not already included:
    ```bash
    python -m ensurepip --upgrade
    ```

- **Kafka 3.6.0**: [Download Kafka](https://kafka.apache.org/downloads)
  - Follow the [Kafka Quickstart Guide](https://kafka.apache.org/quickstart) for installation and setup instructions.
  - [Kafka Ubuntu Installation](https://www.digitalocean.com/community/tutorials/how-to-install-apache-kafka-on-ubuntu-20-04))

- **MQTT- mosquitto 2.0.11**: 
  - We use the 'paho-mqtt' library in Python. Follow the [mqtt guide](https://mosquitto.org/blog/2021/06/version-2-0-11-released/)
  - Install it using 'pip':
    ```bash
    pip install paho-mqtt
    ```
- **GUI- pyqt6**:
- Install it using 'pip':
    ```bash
    pip install pyqt6
    ```
    ---
## Step 3: Start Kafka Server
Follow the Kafka Quickstart Guide to start the Kafka server. [Kafka Quickstart Guide](https://kafka.apache.org/quickstart)

## Step 4: Run the Tool
```bash
python main.py
```














