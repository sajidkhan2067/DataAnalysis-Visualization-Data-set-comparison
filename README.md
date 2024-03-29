## Project Overview

The project focuses on visualizing key features in datasets using box plots, specifically highlighting flow characteristics measured by CICFlowMeter. Flows in network traffic represent sequences of related data packets with common attributes like IP addresses, port numbers, and transport protocols. The README includes figures depicting total packets transmitted in both forward and backward directions, along with an overview of the overall volume of packet traffic in the datasets.

Additionally, a figure provides insights into the average packet size by illustrating the mean value of the total packet length. The box plots reveal similar distributions between attack and benign traffic in the generated datasets, presenting challenges for rule-based detection models. The overlapping distributions underscore the complexity of accurately classifying attacks, necessitating the development of advanced detection techniques to combat emerging threats.

## Experimented Datasets

- **Dataset-2:** [Dos/DDoS Attack Dataset for 5G Network Slicing](https://ieee-dataport.org/documents/dosddos-attack-dataset-5g-network-slicing)
   - Attack Traffic: 5 Million
   - Benign Traffic: 6 Million

- **Dataset-3:** [Dos/DDoS Attack Dataset for 5G Network Slicing](https://ieee-dataport.org/documents/dosddos-attack-dataset-5g-network-slicing)
   - Attack Traffic: 5 Million
   - Benign Traffic: 6 Million

- **CICDDoS2019:** [CIC DDoS Dataset 2019](https://www.unb.ca/cic/datasets/ddos-2019.html)
   - Attack Traffic: 1 Million
   - Benign Traffic: 2 Million

- **5G NIDD:** [5G NIDD Comprehensive Network Intrusion Detection Dataset](https://ieee-dataport.org/documents/5g-nidd-comprehensive-network-intrusion-detection-dataset-generated-over-5g-wireless)
   - Attack Traffic: Not taken
   - Benign Traffic: 15,000

- **5GAD-2022:** [5GAD-2022 on GitHub](https://github.com/IdahoLabResearch/5GAD)
   - Attack Traffic: Not taken
   - Benign Traffic: 84,000

## Visualization:
Some of the box plots are shown below:
# Forward Packet Length Std:
![Forward Packet Length Std](https://github.com/sajidkhan2067/DataAnalysis-Visualization-Data-set-comparison/assets/8274006/22812dda-996d-4da9-b286-b641e396e02d)

# Packet Length Mean:
![Packet Length Mean](https://github.com/sajidkhan2067/DataAnalysis-Visualization-Data-set-comparison/assets/8274006/cb12e48c-4573-4a89-9ba3-b970cbd89113)

# Protocol:
![Protocol](https://github.com/sajidkhan2067/DataAnalysis-Visualization-Data-set-comparison/assets/8274006/ce6c33e4-483f-46e3-aa8b-4e4c88ed0122)

# Total Forward Packet:
![Total Forward Packet](https://github.com/sajidkhan2067/DataAnalysis-Visualization-Data-set-comparison/assets/8274006/7b6bfeec-fdb1-478d-a2a2-17e001b91c1a)

# Total Backward Packet:
![Total Backward Packet](https://github.com/sajidkhan2067/DataAnalysis-Visualization-Data-set-comparison/assets/8274006/264fdffe-bd14-4877-9a61-36a540ce8689)

