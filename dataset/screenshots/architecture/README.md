## System Architecture

This folder describes the overall system architecture of the **Student Mental Health Detection System**, developed as a final year academic project.

The system is designed using a **three-tier architecture** to ensure modularity, scalability, and clear separation of responsibilities.

### Architecture Layers

1. **Frontend Layer**
   - Provides a form-based user interface for students
   - Collects academic, lifestyle, and stress-related inputs
   - Sends data securely to the backend API

2. **Backend Layer**
   - Acts as an API layer for handling requests
   - Validates user inputs
   - Communicates with the machine learning model
   - Returns prediction results to the frontend

3. **Machine Learning Engine**
   - Contains the trained machine learning model
   - Handles data preprocessing and feature transformation
   - Generates mental health risk predictions

This layered design improves maintainability and allows individual components to be updated independently.
