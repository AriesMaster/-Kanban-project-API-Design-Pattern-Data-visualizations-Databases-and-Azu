# Kanban project , API , Design Pattern, Data visualizations, Databases and Azure
# Project Repository ReadMe

This repository contains the project files for Project 2, along with detailed information about the setup, functionality, and usage of the API. The API is designed to manage customer information, orders, and products.

## Project2 repo Overview

Project 2 aims to create a comprehensive API for managing customers, orders, and products. The API is built using .NET Core and utilizes an Azure SQL Server database for data storage.

## Repository Structure

- `src/` directory: Contains the source code for the API project.
- `scripts/` directory: Includes SQL scripts for database setup.
- `docs/` directory: Houses project documentation and related files.

## Getting Started

1. **Database Setup**: Create a SQL Server with a secure service account username and password on Azure. Set up the necessary tables using the provided SQL scripts.

2. **API Project Setup**: Clone this repository and set up a new .NET Core Web API project. Connect the API to the database, and apply dependency injection.

3. **Functionality**: Implement customer, order, and product management functionality according to the specified requirements. Build GET, POST, PATCH, and DELETE methods for each entity.

4. **Security**: Implement authentication to restrict access to the API. Ensure no credentials are stored on GitHub.

5. **Web API Cloud Hosting**: Create an API service connected to an F1 tier (free) service plan on Azure. Publish your API to the service and ensure it is secure and accessible.

6. **Project Documentation**: The `docs/` directory contains important project documentation, including how to use the API, a list of all endpoints, and additional implemented aspects.


# Project 3 Repository 

Welcome to the CMPG 323 Project 3 repository! This project focuses on developing a specialized API that efficiently manages data related to orders, customers, and products. The API is designed using the latest .NET Core technology and leverages Azure services for secure data storage and access.

## Repository Structure

- `src/` directory: Contains the source code for the specialized API project.
- `docs/` directory: Includes important project documentation and related files.

## Getting Started

1. **GitHub Repository Setup**: Start by creating a new repository named 'CMPG 323 Project 3 - <your-student-number>' and add a descriptive `ReadMe.md` file to introduce your project.

2. **Project Progress**: Regularly commit and push your solution to the source control throughout the development process. Keep the GitHub project updated iteratively to showcase the progression of your project.

3. **Project Setup**: Fork the existing GitHub repository and create a new development branch. Connect the Web App to the designated data source by adding the connection string to the `appsettings.json` file.

4. **Design Pattern Implementation**: Develop repository classes that will manage data access operations for orders, customers, and products. Transfer relevant data access operations from the controllers to these repository classes.

5. **Implement Repository Classes**: Implement the usage of the repository classes in the respective controllers to replace transferred data access operations.

6. **Security**: Ensure that no sensitive credentials are stored within the repository, maintaining the security of your project.

7. **Web API Cloud Hosting**: Create an App Service connected to an F1 tier (free) service plan on Azure. Publish your App to the service, making sure it's secure and accessible to users.

8. **Project Documentation**: Detail how users can interact with your App in the `ReadMe.md` file. Additionally, compile a list of all visited sites used for the project in a reference list document.


# CMPG 323 Project 4 Repository 

Welcome to the CMPG 323 Project 4 repository! This project focuses on creating a UiPath process for user acceptance testing in a connected office web application. Utilize UiPath Studio to automate user interactions and ensure smooth testing.

## Repository Structure

- `src/` directory: Contains the source code for the UiPath process.
- `docs/` directory: Includes vital project documentation and related files.

## Getting Started

1. **GitHub Repository Setup**: Start by creating a new repository named 'CMPG 323 Project 4 - <your-student-number>' and add an informative `ReadMe.md` file to provide an overview of your project.

2. **Project Progress**: Consistently commit and push your solution to the source control during the development phase. Maintain an updated GitHub project to illustrate the iterative progress of your project.

3. **Project Setup**: Clone the repository and create the necessary UiPath process. Install UiPath Studio and set up your project accordingly.

4. **User Acceptance Testing**: Utilize UiPath Studio to read input data from Excel and iterate over it. Automate user interactions with the web application to simulate user acceptance testing.

5. **UI Automation**: Automate the process of entering data into the web application's fields to create a new record. Submit the data to create records and navigate to view the newly created records.

6. **Record Results**: Update the data table with the results of user acceptance testing. Update the Excel spreadsheet with testing outcomes.

7. **Project Close-out**: Publish the UiPath solution to the UiPath Orchestrator for deployment.

8. **Project Documentation**: Explain how stakeholders can use and benefit from the UiPath process in the `ReadMe.md` file. Maintain a reference list document for your sources.


# CMPG 323 Project 5 Repository 

Welcome to the CMPG 323 Project 5 repository! This project focuses on creating a Power BI report for EcoPower Logistics that provides insightful visualizations and data monitoring for orders, products, and customers.

## Repository Structure

- `src/` directory: Contains the Power BI report files.
- `docs/` directory: Holds significant project documentation and associated files.

## Getting Started

1. **GitHub Repository Setup**: Start by creating a new repository named 'CMPG 323 Project 5 - <your-student-number>'. Add an informative `ReadMe.md` file to introduce your project.

2. **Project Progress**: Regularly commit and push your report files to source control during the development. Keep the GitHub project updated iteratively to display the progression of your project.

3. **Project Setup**: Clone the repository and create the Power BI report. Install Power BI Desktop and set up your project accordingly.

4. **Configure the Report**: Develop different pages for high-level metrics, order monitoring, product monitoring, and customer monitoring.

5. **Data Connection**: Set up a secure live connection to the data sources you'll use for the visualizations. Ensure appropriate data mapping.

6. **Implement Data Manipulation**: Clean the datasets, remove duplicates, associate data fields with correct data types, and create calculated columns and key measures.

7. **Report Development**: Create various visualizations for different pages, including high-level metrics, order monitoring, product monitoring, and customer monitoring.

8. **Filtering**: Implement filters that can be applied across pages and visuals. Add filters based on product category, customer, and order number.

9. **Project Close-out**: Complete the project by finalizing your Power BI report and preparing it for documentation.

10. **Project Documentation**: Describe how stakeholders can use and benefit from the Power BI report in the `ReadMe.md` file. Compile a reference list document for your sources.

Certainly, I'll incorporate the additional information you provided into the README for each project:

## Project 2 Repository ReadMe

Welcome to the CMPG 323 Project 2 repository! This project focuses on building a comprehensive API for customer, order, and product management.

### Branching Strategy

We will be using the Gitflow branching strategy for this project. The `main` branch will be our production branch, while `develop` will serve as the development branch. Feature branches will be created from `develop` for each specific feature or task.

### .gitignore File

A `.gitignore` file is included in the repository to exclude certain files or directories from version control. This ensures that sensitive information like credentials, compiled files, and other temporary files are not stored in the repository.

### Storage of Credentials and Sensitive Information

For security reasons, sensitive information such as database connection strings, API keys, and passwords should never be directly stored in the repository. Instead, use environment variables, configuration files, or a secure key vault to manage and access these credentials during runtime.

## Project 3 Repository ReadMe

Welcome to the CMPG 323 Project 3 repository! This project focuses on creating a specialized UiPath process for user acceptance testing.

### Branching Strategy

Similar to Project 2, we will be using the Gitflow branching strategy. The `main` branch is reserved for production, and `develop` serves as the development branch. Feature branches will be created from `develop` for specific tasks.

### .gitignore File

The repository includes a `.gitignore` file to exclude unnecessary files and directories from version control. This helps to prevent sensitive information and temporary files from being committed.

### Storage of Credentials and Sensitive Information

Just like in Project 2, sensitive information should never be directly stored in the repository. Utilize secure methods such as environment variables or configuration files to manage credentials and other sensitive data securely.

## Project 4 Repository ReadMe

Welcome to the CMPG 323 Project 4 repository! This project focuses on creating insightful visualizations using Power BI for EcoPower Logistics.

### Branching Strategy

For this project, we will stick to the Gitflow branching strategy. The `main` branch is for production, and `develop` is the development branch. Feature branches will be derived from `develop`.

### .gitignore File

Included in the repository is a `.gitignore` file. This file is crucial for excluding sensitive files and data that should not be part of version control.

### Storage of Credentials and Sensitive Information

Sensitive information should never be directly included in the repository. Instead, opt for secure methods like environment variables or configuration files to handle and access credentials and sensitive data appropriately.

## Project 5 Repository ReadMe

Welcome to the CMPG 323 Project 5 repository! This project focuses on creating a Power BI report for EcoPower Logistics' data visualization.

### Branching Strategy

We're employing the Gitflow branching strategy here as well. The `main` branch is used for production, while `develop` is the development branch. Feature branches will be created from `develop`.

### .gitignore File

In the repository, you'll find a `.gitignore` file to exclude unnecessary and sensitive files from being tracked by Git.

### Storage of Credentials and Sensitive Information

As with the previous projects, sensitive information should not be stored directly in the repository. Adopt secure approaches like environment variables or configuration files to manage sensitive data effectively.






