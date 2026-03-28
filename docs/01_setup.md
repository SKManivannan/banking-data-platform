# Setup Documentation

## Environment Setup

### WSL Setup

* Installed WSL (Ubuntu)
* Updated packages using:
  sudo apt update

### Java Installation

* Installed OpenJDK 17 in WSL for Kafka

### Python Environment

* Created virtual environment:
  python3 -m venv venv

* Activated:
  source venv/bin/activate

### Dependencies Installed

* kafka-python
* faker
* pyspark

### Requirements File

Generated using:
pip freeze > requirements.txt

## Learnings

* Isolated environments are critical for reproducibility
* Kafka requires Java runtime

