# Smartshield: TSYP 12 Technical Challenge

## About Us
Smartshield is a cutting-edge cybersecurity solution designed to monitor, analyze, and detect network anomalies in real-time. Our platform leverages powerful technologies, including machine learning and generative AI, to provide actionable insights into network traffic, helping organizations stay ahead of emerging threats. Through our innovative use of Docker, containerization, and scalable microservices, we aim to simplify the management of network security, making it more accessible and efficient.

## Our Mission
Our mission is to revolutionize network security monitoring through seamless automation, intelligent anomaly detection, and insightful reporting. By combining machine learning, generative AI, and an intuitive UI, Smartshield-INSAT aims to empower enterprises to proactively detect and mitigate potential security threats in their networks, enhancing both security and operational efficiency.

## Repositories
Explore the various components of the Smartshield-INSAT project:

- **Frontend**: [Smartshield-INSAT/Frontend](https://github.com/Smartshield-INSAT/Frontend)
- **Backend**: [Smartshield-INSAT/Backend](https://github.com/Smartshield-INSAT/Backend)
- **ML Engine**: [Smartshield-INSAT/MLEngine](https://github.com/Smartshield-INSAT/MLEngine)
- **Report Generator**: [Smartshield-INSAT/Report-Generator](https://github.com/Smartshield-INSAT/Report-Generator)
- **Logs Extraction**: [Smartshield-INSAT/Logs-Extraction](https://github.com/Smartshield-INSAT/Logs-Extraction)
- **Prototype**: [Smartshield-INSAT/Prototype](https://github.com/Smartshield-INSAT/Prototype)

## System Overview
The Smartshield-INSAT project simulates an entire architecture using Docker containers, providing a robust environment with several key services for monitoring and analyzing network traffic. The architecture is built to provide a comprehensive view of network activities, from log collection to threat analysis and reporting.
![alt text](image.png)

This project sets up an infrastructure with the following services:

- **Elasticsearch**: A powerful search engine for indexing and querying data.
- **Kibana**: A visualization tool to explore data stored in Elasticsearch.
- **RabbitMQ**: A message broker with a management interface.
- **PCAP Processor** (our image): A custom service for processing PCAP files with (zeek/argus/pyshark).
- **Frontend**: A React-based application that provides an interface for interacting with the data and services. 
- **Backend**: A NestJS application that serves as the API layer, managing communication between the frontend, PCAP Processor, ML Models.
- **ML Engine**: A machine learning model for detecting anomalies in the network, used to identify potential threats or irregularities.
- **Generative AI Report Generator**: An AI-driven tool that generates detailed reports based on processed data, providing insights into detected anomalies or patterns.

## Demo Video
Watch a walkthrough of the project setup and functionality in our 
[Demo Video](https://youtu.be/2Nd6C_SpXak).

## Team Structure
Our team consists of a group of passionate and skilled developers working together to create the Smartshield-INSAT solution. We collaborate closely, drawing from expertise in cybersecurity, machine learning, cloud technologies, and software development to ensure that our project is both technically sound and highly impactful.
- Kacem Mathlouthi
- Fayez Zouari
- Mohamed Amine Haouas
- Youssef Abid
- Mohamed Masmoudi
- Iyed Medimegh
- Achref Ben Ammar
- Raed Addala 

## Get Involved
We welcome contributions from developers, security researchers, and other stakeholders interested in enhancing network security tools and technologies. Here’s how you can get involved:
- **Contribute Code**: Fork the repositories, submit pull requests, or suggest improvements.
- **Report Bugs**: Found an issue? Let us know by submitting a bug report.
- **Join Discussions**: Engage with the community by participating in our GitHub discussions.
- **Help with Documentation**: If you can help improve our documentation, we encourage you to contribute!

## Acknowledgments
The authors would like to thank the IEEE INSAT Student Branch Computer Society for providing resources and support throughout this project. Special appreciation is extended to INSAT for its invaluable assistance in creating the SMARTSHIELD platform. Our gratitude also goes to Dr. Lilia Sfaxi for her guidance and constructive feedback during the development and review process.

- **Docker & Docker Compose**: For containerizing services and ensuring a consistent development environment.
- **Elasticsearch & Kibana**: For providing powerful tools to manage and visualize network data.
- **RabbitMQ**: For efficient log data collection and message brokering.
- **Zeek/Argus/Pyshark**: For their role in PCAP file processing and network traffic analysis.
- **NestJS**: For its powerful backend framework that powers the API layer.
- **React**: For the frontend interface that allows seamless interaction with the platform.
- **Machine Learning Libraries**: Used to detect network anomalies and potential security threats.
We would also like to thank the open-source community for providing the tools and resources that were integral to the success of this project.
