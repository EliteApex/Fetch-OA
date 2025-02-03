# Fetch OA - Running Instructions

## How to Run This Code Using Docker

To run this project using Docker, follow these steps:

### **1. Pull the Pre-Built Docker Image**
Download the pre-built Docker image from Docker Hub:
```bash
docker pull eliteapex/fetch-oa
```

### **2. Run the Docker Container**
Execute the following command to start the container and expose Jupyter Notebook on port 8888:
```bash
docker run -p 8888:8888 eliteapex/fetch-oa
```

### **3. Access Jupyter Notebook**
Once the container is running, open the following URL in your browser:
```
http://localhost:8888
```

This will allow you to access the Jupyter Notebook (`tasks_oa.ipynb`) and run the code interactively.

