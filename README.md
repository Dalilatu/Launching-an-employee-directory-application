# AWS Employee Directory Web Application

## 1. Project Overview

This project involves deploying an Employee Directory web application on Amazon Web Services (AWS). The application is based on a practical cloud computing lab and demonstrates how to deploy a web application using AWS networking and compute resources.<br/>

The initial implementation focuses on hosting the application on an Amazon EC2 instance within a Virtual Private Cloud (VPC), with internet connectivity configured through an Internet Gateway and VPC route tables.<br/>

The project will be extended to incorporate additional AWS services for database integration, monitoring, and DNS management.<br/>

## 2. Project Objectives

The main objectives of this project are to:

- Deploy an Employee Directory web application on AWS.
- Understand AWS Regions and Availability Zones.
- Create and configure a Virtual Private Cloud (VPC).
- Configure an Internet Gateway and route tables for network connectivity.
- Launch and configure an Amazon EC2 instance.
- Understand how AWS networking components work together.
- Explore database integration for employee information.
- Implement monitoring and observability using Amazon CloudWatch.
- Configure DNS resolution using Amazon Route 53.
- Identify security considerations when hosting a publicly accessible web application.

## 3. AWS Services and Infrastructure

The project uses or plans to incorporate the following AWS services:

| AWS Service or Component | Purpose |
|---|---|
| AWS Region | Provides the geographical location for AWS resources. |
| Availability Zone | Provides an isolated location within an AWS Region for deploying resources. |
| Amazon VPC | Provides an isolated virtual network for AWS resources. |
| Internet Gateway | Enables internet connectivity for resources with appropriate routing and security configuration. |
| VPC Route Table | Defines how network traffic is directed. |
| Amazon EC2 | Hosts the Employee Directory web application. |
| Amazon RDS or another database service | Planned integration for storing employee information. |
| Amazon CloudWatch | Planned monitoring of application and infrastructure metrics and logs. |
| Amazon Route 53 | Planned DNS management for accessing the application through a domain name. |

## 4. System Architecture

The initial architecture consists of an EC2 instance hosting the Employee Directory application inside a VPC.

### Initial Architecture Flow

                 Internet
                    |
                    |
             Internet Gateway
                    |
                    |
              VPC Route Table
                    |
                    |
             Amazon EC2 Instance
                    |
                    |
         Employee Directory Website
