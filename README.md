# employee-service — TypeScript / Express
Build locally: `npm install && npm run build && npm start`
Health: `curl http://localhost:3000/health`; API: `curl http://localhost:3000/api/employees`
Build Docker image: `docker build -t employee-service:1.0.0 .`
Replace `YOUR_DOCKERHUB_USERNAME` in Kubernetes YAML, then `kubectl apply -f k8s/deployment.yaml`.
