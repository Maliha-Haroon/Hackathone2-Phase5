# Backend Container Spec

Base Image: python:3.11-slim  
Working Directory: /app  
Expose Port: 8000  

Build Steps:
1. Copy requirements.txt
2. Install dependencies
3. Copy source code
4. Start FastAPI with uvicorn
