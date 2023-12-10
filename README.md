# HallPass Django Application

![HallPass Logo](hallpass_logo.png)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The HallPass Django Application is a school safety tool designed to enhance security and supervision in educational institutions. It helps schools keep track of when students leave their classrooms to go to the hallway, ensures that students who should not be unsupervised together are not, and enforces a limit on the number of students allowed in the hallways at any given time.

This README provides an overview of the HallPass application, its features, installation instructions, and configuration details.

## Features

### 1. Hallway Access Control
- Track and record when students leave their classrooms to go to the hallway.
- Ensure that only authorized students are allowed in the hallways.
- Implement time-based restrictions to prevent unsupervised hallway access during specific periods.

### 2. Student Supervision
- Define rules and restrictions to prevent students from being unsupervised together in the hallways.
- Ensure that students are accompanied by a staff member or follow specific protocols when necessary.

### 3. Hallway Occupancy Limit
- Set and enforce a maximum occupancy limit for the hallways to maintain a safe and orderly environment.
- Automatically restrict hallway access when the maximum occupancy is reached.

## Usage

To use the HallPass application, follow these general steps:

1. Log in as an administrator or staff member with appropriate privileges.

2. Configure hallway access rules, supervision requirements, and occupancy limits in the application settings.

3. Monitor hallway access and occupancy in real-time through the HallPass dashboard.

4. Generate reports and notifications for any violations or incidents.

## Configuration

You can customize the HallPass application by modifying the configuration settings in the `settings.py` file. This includes setting up user roles, defining hallway access rules, specifying supervision requirements, and configuring occupancy limits.

Refer to the [Django documentation](https://docs.djangoproject.com/en/3.2/topics/settings/) for more details on configuring Django applications.

## Contributing

We welcome contributions to the HallPass Django Application. If you would like to contribute to the development, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature/new-feature

## License

HallPass is licensed under the terms of the GNU General Public License (GNU GPL) Version 3. You can find a copy of the GNU GPL in the [LICENSE](LICENSE) file included with this software.

The GNU GPL is a free and open-source software license that grants you the freedom to use, modify, and distribute this software, subject to the conditions of the license. Please review the full text of the GNU GPL to understand your rights and responsibilities.
