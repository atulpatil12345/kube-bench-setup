# Prerequisites

## Tools and Setup
1. **Kubernetes Cluster**:
   - Version: v1.23+
   - Nodes: 3 worker nodes, 1 master node
   - Cloud Provider: [e.g., AWS, GCP, or on-premises]

2. **kubectl**:
   - Installed and configured with cluster admin privileges.

3. **Kube-bench**:
   - Official Docker image: `aquasec/kube-bench:latest`.

4. **Access**:
   - Ensure your `kubectl` user has permissions to deploy resources and view logs.

5. **YAML Files**:
   - Downloaded job definition from the [Kube-bench repository](https://github.com/aquasecurity/kube-bench).

## Environment Details
- OS: Ubuntu 20.04
- Cloud Platform: AWS
- Storage: EBS for persistent volumes
- CNI Plugin: Calico

