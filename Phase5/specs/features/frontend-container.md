# Frontend Container Spec

Base Image: node:20-alpine  
Working Directory: /app  
Expose Port: 3000  

Build Steps:
1. Copy package.json
2. Install dependencies
3. Build Next.js app
4. Start with `npm start`
