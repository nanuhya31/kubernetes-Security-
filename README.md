# kubernetes-Security-
Install local K8s cluster (such as Minikube, K3s, Kind, etc) and use a tool such as Kubescape (or any other tool) to scan for findings and send the list of the findings.

Task:
Install a local K8s cluster and run a security scan using tools like Kubescape.
Deliverables:
A JSON file with the findings

✅ Example command (Kubescape):
kubescape scan framework nsa --output json --output-file results.json
✅ To run locally:
Set up a local K8s cluster (e.g., with Minikube):
minikube start
Install Kubescape:
curl -s https://raw.githubusercontent.com/kubescape/kubescape/master/install.sh | /bin/bash



