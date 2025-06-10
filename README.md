
# KCNA Practice Test – Kubernetes and Cloud Native Associate

This is a collection of real-style KCNA (Kubernetes and Cloud Native Associate) multiple-choice questions, based on previously seen exam content. Each question includes a correct answer and is ideal for practice or revision.

---

## 📋 Instructions
- Read each question carefully.
- Try to answer it yourself before revealing the correct answer.
- Click on the collapsible "Show Answer" section to check your response.

---

### ✅ Questions

<details>
<summary><strong>1. What methods can you use to scale a deployment?</strong></summary>

✅ Correct Answer: `With kubectl scale deployment and kubectl edit deployment.`  
</details>

<details>
<summary><strong>2. Which of the following options includes valid API versions?</strong></summary>

✅ Correct Answer: `alpha1, beta3, v2`  
</details>

<details>
<summary><strong>3. Which is an industry-standard container runtime with emphasis on simplicity, robustness, and portability?</strong></summary>

✅ Correct Answer: `cri-o`  
</details>

<details>
<summary><strong>4. Services and Pods in Kubernetes are ______ objects.</strong></summary>

✅ Correct Answer: `YAML`  
</details>

<details>
<summary><strong>5. Can a Kubernetes Service expose multiple ports?</strong></summary>

✅ Correct Answer: `Yes, but you must specify an unambiguous name for each port.`  
</details>

<details>
<summary><strong>6. Which of the following capabilities are allowed using the Restricted policy?</strong></summary>

✅ Correct Answer: `NET_BIND_SERVICE`  
</details>

<details>
<summary><strong>7. What is a probe within Kubernetes?</strong></summary>

✅ Correct Answer: `A diagnostic performed periodically by the kubelet on a container.`  
</details>

<details>
<summary><strong>8. What’s the default deployment strategy in Kubernetes?</strong></summary>

✅ Correct Answer: `RollingUpdate`  
</details>

<details>
<summary><strong>11. Which is a definition of Hybrid Cloud?</strong></summary>

✅ Correct Answer: `A cloud native architecture that uses a combination of services running in different public and private clouds, including on-premises data centers.`  
</details>

<details>
<summary><strong>12. Who is normally responsible for incident management in cloud-native systems?</strong></summary>

✅ Correct Answer: `Site Reliability Engineers (SREs)`  
</details>

<details>
<summary><strong>15. How do you deploy a workload to Kubernetes without additional tools?</strong></summary>

✅ Correct Answer: `Create a manifest and apply it with kubectl.`  
</details>

<details>
<summary><strong>17. Which command is used to retrieve field documentation for a Kubernetes resource?</strong></summary>

✅ Correct Answer: `kubectl explain`  
</details>

<details>
<summary><strong>18. What does SIG stand for in Kubernetes?</strong></summary>

✅ Correct Answer: `Special Interest Group`  
</details>

<details>
<summary><strong>19. Which tasks are performed by a container orchestration tool?</strong></summary>

✅ Correct Answer: `Schedule, scale, and manage the health of containers.`  
</details>

<details>
<summary><strong>20. What fields must exist in any Kubernetes object file?</strong></summary>

✅ Correct Answer: `apiVersion, kind, metadata`  
</details>

<details>
<summary><strong>24. How does dynamic storage provisioning work?</strong></summary>

✅ Correct Answer: `A user requests dynamically provisioned storage by including an existing storage class in their PersistentVolumeClaim.`  
</details>

<details>
<summary><strong>25. What is the lightweight Kubernetes distribution for edge computing?</strong></summary>

✅ Correct Answer: `k3s`  
</details>

<details>
<summary><strong>26. Which type of Service requires manual creation of Endpoints?</strong></summary>

✅ Correct Answer: `Services without selectors`  
</details>

<details>
<summary><strong>28. Why is Cloud Native Architecture important?</strong></summary>

✅ Correct Answer: `It removes constraints to rapid innovation.`  
</details>

<details>
<summary><strong>29. Which is a governance board responsibility in open source?</strong></summary>

✅ Correct Answer: `Outline the project's “terms of engagement”.`  
</details>

<details>
<summary><strong>30. What is a Kubernetes Service Endpoint?</strong></summary>

✅ Correct Answer: `It is an object that gets IP addresses of individual Pods assigned to it.`  
</details>

<details>
<summary><strong>32. Which Prometheus metric can go up and down?</strong></summary>

✅ Correct Answer: `Gauge`  
</details>

<details>
<summary><strong>34. What are the most important resources for etcd performance?</strong></summary>

✅ Correct Answer: `Network throughput and CPU`  
</details>

<details>
<summary><strong>35. Which kubectl command shows CPU and memory usage?</strong></summary>

✅ Correct Answer: `kubectl top`  
</details>

<details>
<summary><strong>36. Which command shows logs of a previously terminated container?</strong></summary>

✅ Correct Answer: `kubectl logs -p -c ruby web-1`  
</details>

<details>
<summary><strong>37. How do you execute a command in a running Pod?</strong></summary>

✅ Correct Answer: `kubectl exec <pod> -- <command>`  
</details>

<details>
<summary><strong>39. What best describes cloud native service discovery?</strong></summary>

✅ Correct Answer: `A mechanism for applications and microservices to locate each other on a network.`  
</details>

<details>
<summary><strong>40. What component assigns external IPs in cloud-hosted Kubernetes?</strong></summary>

✅ Correct Answer: `Cloud Controller Manager`  
</details>

<details>
<summary><strong>43. What is a sidecar container?</strong></summary>

✅ Correct Answer: `A container that runs next to another container within the same Pod.`  
</details>

<details>
<summary><strong>44. Which tool manages traffic flow and access policies in Kubernetes?</strong></summary>

✅ Correct Answer: `kube-proxy`  
</details>

<details>
<summary><strong>45. What handles network communication using OS packet filters?</strong></summary>

✅ Correct Answer: `kube-proxy`  
</details>

<details>
<summary><strong>47. What influences Pod scheduling?</strong></summary>

✅ Correct Answer: `Pod memory requests, node taints, and Pod affinity.`  
</details>

<details>
<summary><strong>48. What are the primary modes of service discovery in Kubernetes?</strong></summary>

✅ Correct Answer: `Environment variables and DNS`  
</details>

<details>
<summary><strong>49. Which component runs containers?</strong></summary>

✅ Correct Answer: `CRI-O`  
</details>

<details>
<summary><strong>51. What is the default authorization-mode in API server?</strong></summary>

✅ Correct Answer: `--authorization-mode=AlwaysAllow`  
</details>

<details>
<summary><strong>52. Which resource uses the 'immutable' field?</strong></summary>

✅ Correct Answer: `ConfigMap`  
</details>

<details>
<summary><strong>53. Which statement about the Kubernetes network model is correct?</strong></summary>

✅ Correct Answer: `Pods can communicate with all Pods without NAT.`  
</details>

<details>
<summary><strong>54. Which command explains the 'replicas' field in Deployment spec?</strong></summary>

✅ Correct Answer: `kubectl explain deployment.spec.replicas`  
</details>

<details>
<summary><strong>56. What packages sets of containers for scheduling?</strong></summary>

✅ Correct Answer: `Deployment`  
</details>

<details>
<summary><strong>57. What defines a logical set of Pods and access policy?</strong></summary>

✅ Correct Answer: `Service`  
</details>

