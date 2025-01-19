
# SBA: A Swift and Stealthy Backdoor Attack Framework for Federated Learning

This repository contains the implementation of **SBA**: a Swift and Stealthy Backdoor Attack Framework for Federated Learning.

### **Overview**
Federated Learning (FL) enables collaborative model training while protecting the privacy of individual participants. However, this decentralized framework is vulnerable to certain risks, particularly backdoor attacks. In such attacks, malicious actors embed triggers into the global model, causing incorrect classifications for inputs with specific features.
Traditional backdoor attacks typically use uniform triggers, which makes them more likely to be detected. Furthermore, These methods tend to overlook the fact that poisoned samples may cause abnormal confidence levels in non-target classes. These methods also require an extended attack window to achieve the desired success rate, which reduces their efficiency and increases the chances of detection.
This paper introduces a novel backdoor attack method called Swift Backdoor Attack (SBA), designed to overcome these challenges. SBA improves both the stealth and success rate of backdoor attacks by generating adaptive triggers tailored to specific inputs. It also incorporates Non-Target Class Suppression (NTCS) loss and an entropy gain mechanism to enhance the attack’s effectiveness.
Our approach suppresses unnecessary activations in the neural network when encountering poisoned samples, making the attack harder to be detected. Experimental results demonstrate that this method significantly increases the success rate of backdoor attacks within a shorter attack window, while evading existing detection mechanisms. This provides a more efficient and covert strategy for executing backdoor attacks in FL.

### **Upcoming Release**
The full implementation of the code and the datasets will be made available shortly. Please stay tuned for updates.
