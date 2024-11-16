# Installation Instructions

## Step 1: Clone This Repository
```bash
git clone https://github.com/atulpatil12345/kube-bench-setup.git
cd kube-bench-setup

# Apply the File: Run the following command to deploy Kube-bench in your cluster:
kubectl apply -f job.yaml

# Monitor the Job: Check the status of the job to ensure it runs successfully:
kubectl get jobs

#View the Logs: Retrieve the output of the Kube-bench job:
kubectl logs job/kube-bench > kube-bench-output.json


