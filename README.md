# Ed-Fed:A generic federated learning (FL) framework with resource aware client selection for edge devices
Ed-Fed is a generic FL framework, which has a single machine simulator for FL and also a real world FL system which can support heterogeneous edge devices such as desktop computers, laptops, and android-based mobile phones as client devices. We provide a complete methodology for training both full and sub-models on mobile phones or anyother edge devices with support for FL related functionalities. We integrated various server strategy algorithms such as Fedavg, Fedprox, FedAdam, FedBN, FedAdagrad etc, and a word error rate (WER) based aggregation strategy for ASR tasks to our custom Ed-Fed framework. We also developed a resource-aware waiting time optimized client selection algorithm that considers the system resources such as computation, storage, power, and phone-specific capabilities of the client devices. We showed that our algorithm can adaptively choose the number of training epochs for the chosen clients while considering the available resources, and thus has the ability to handle stragglers.

For more details: Please reach out to us and have a look at our paper : Ed-Fed: A generic federated learning framework with resource-aware client selection for edge devices, Published in: 2023 International Joint Conference on Neural Networks (IJCNN), DOI: 10.1109/IJCNN54540.2023.10191316

# Results:
![image](https://github.com/user-attachments/assets/c325b042-d6fd-44bb-b35b-75993656520f)
Performance of Ed-Fed using mobile phones as client devices: Comparison of average WER on global test set versus FL rounds using our proposed resource-aware client selection approach

