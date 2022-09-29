# localstack-helm-chart
helm chart to run localstack locally


Steps to run localstack:
 
 1. Setup Kubernetes environment
 2. helm dependency update ./ (run the command from inside this repo)
 3. helm install localstack ./
 4. port forward to access it locally.
