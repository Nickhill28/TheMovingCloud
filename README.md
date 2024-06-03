# TheMovingCloud
UHackHive Submission for prototype phase.

Local Business Marketplace Prototype - UHackHive
This repository contains the code and documentation for a prototype of a local business marketplace built using Google Cloud Platform (GCP) for the UHackHive competition. The goal of this prototype is to address the problem of dead stocks and irrelevant shopping sprees by connecting local businesses with relevant customers.

Features
The prototype implements the following features:

Automated Tagging and Tag-Based Billing: A dashboard that uses automated tagging and tag-based billing to help local businesses manage their inventory and pricing more effectively.
Targeted Traffic: Restricts incoming traffic to specific locations to ensure that local businesses only serve customers within their target audience.
Personalized Virtual Marketplaces: Uses GenAI tools to create a unique virtual marketplace for each customer, showcasing businesses and products relevant to their needs.
Architecture
The architecture of the prototype is based on a client-server model with the following components:

Business Owner Server: A server hosted on GCP that manages the business owner's data, including inventory, pricing, and target audience.
Client-Side Server: A server hosted on GCP that handles client requests, processes searches, and generates personalized virtual marketplaces.
Global Server: A server that acts as a central point for managing communication and ensuring security.
Database: A database stored on GCP to manage data for the application.
Technologies
The prototype utilizes various GCP services and technologies, including:

Compute Engine: For hosting virtual machines for the servers.
Virtual Private Cloud (VPC): For configuring network settings and access control.
Cloud Load Balancing: For distributing traffic to servers.
Cloud SQL: For managing the database.
GenAI tools: For generating personalized virtual marketplaces.
Python: As the primary programming language for backend development.
JavaScript: For building the frontend user interface.
Usage
This repository includes a basic implementation of the prototype. To deploy and run it, you will need to:

Set up a GCP project and configure the necessary services.
Deploy the code for the servers and database.
Test the functionality of the prototype.
Future Development
Future development of this prototype could focus on:

Expanding functionality: Adding new features, such as reviews, ratings, and messaging.
Improving scalability: Optimizing the system to handle a larger number of businesses and customers.
Enhancing security: Implementing measures to protect user data and ensure secure communication.
Integration with other platforms: Connecting the marketplace to other e-commerce platforms or social media.
Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

Disclaimer
This prototype is for demonstration purposes only and may not be suitable for production use.

Credits
The prototype was developed by the NicknShe team, under the organization The MovingCloud, as part of the UHackHive competition.

For more detailed information, please refer to the individual files and comments within the code.
