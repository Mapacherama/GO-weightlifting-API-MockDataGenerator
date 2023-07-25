# Weightlifting Tracker API - Mock Data Generator

This repository contains a Go programming project designed to populate a MySQL database with mock data for the Weightlifting Tracker API.

## Overview

The Weightlifting Tracker API is a robust backend designed to provide comprehensive tracking and management for weightlifters. Leveraging the power of .NET and GraphQL, it provides users with the ability to track their weights, nutrition, and overall progress in their weightlifting journey.

The purpose of this Go project is to generate mock data that aligns with the functionalities of the Weightlifting Tracker API, which include:

- **Weight Tracking**: Track weightlifting progress over time, record and update weights lifted, and view progress graphs.
- **Nutrition Management**: Manage daily nutrition intake, set nutrition goals, track macros, and more.
- **User Management**: Create, update, delete, and view user profiles.

## Getting Started

### Prerequisites

- Go programming language
- MySQL database
- Go MySQL driver (`go-sql-driver/mysql`)
- Go fake data generator library (`go-fake`)

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
2. Install Go packages
    ```sh
       go get -u github.com/go-sql-driver/mysql
       go get -u github.com/icrowley/fake

## Usage

After setting up the project and installing the necessary packages, you can run the Go program to generate and insert mock data into your MySQL database.

# Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

1. Fork the Project
2. Create your Feature Branch (```git checkout -b feature/AmazingFeature```)
    Commit your Changes (```git commit -m 'Add some AmazingFeature'```)
    Push to the Branch (```git push origin feature/AmazingFeature```)
    Open a Pull Request

# License

Distributed under the MIT License. See LICENSE for more information.
