# Name-Change-Api

A high-performance, structured Python API utilizing Protocol Buffers (Protobuf) for serialized data exchange, designed for seamless serverless deployment.

## Overview

This repository hosts a lightweight, serverless API that processes incoming data requests using highly optimized structured schemas. By leveraging Protobuf, the API ensures low-latency and strict data-type enforcement, making it ideal for microservices and cross-platform integrations.

## Tech Stack

* Language: Python
* Data Serialization: Google Protocol Buffers (Protobuf)
* Deployment: Vercel (Serverless)

## Repository Structure

* app.py: Main entry point handling API routing and application logic.
* *_pb2.py: Generated Python classes compiled from Protobuf .proto schemas (data, my, output) to manage strict data models.
* requirements.txt: Manages application dependencies.
* vercel.json: Configuration routing rules and runtime definitions for serverless hosting.

## Local Setup

### 1. Clone the Repository
```bash
git clone https://github.com
cd Name-Change-Api
```

### 2. Set Up a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Application
```bash
python app.py
```

## Deployment

The API is fully configured for deployment on the Vercel Serverless platform via the bundled vercel.json routing matrix. 

To deploy using the Vercel CLI:
```bash
npm install -g vercel
vercel
```
