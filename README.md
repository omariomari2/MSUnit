# MSUnit: Stroke Patient Management System

A Django-based web application for mobile stroke units and remote neurologist consultations.

![Project Logo](logo.png)

## 🏥 Project Overview

MSUnit is an innovative web-based clinical management system designed to revolutionize stroke patient care by providing real-time tracking, intelligent alerting, and seamless communication between medical professionals.

### 🎯 Core Mission
Reduce patient response times, minimize documentation errors, and create a comprehensive digital workflow for stroke unit management.

### 🌟 Key Differentiators
- **Real-Time Patient Monitoring**
- **Role-Based Access Control**
- **Intelligent Alert Escalation**
- **Comprehensive Clinical Documentation**

## 🚀 Features

### Patient Management
- Comprehensive patient registration
- Detailed medical history tracking
- Real-time vital sign monitoring
- Automated status transitions

### User Roles & Permissions
#### 👩‍⚕️ Technician Capabilities
- Patient data entry
- Vital sign recording
- Initial triage support

#### 👨‍⚕️ Neurologist Capabilities
- Detailed case review
- Treatment planning
- Alert resolution
- Consultation documentation

### Alert System
- Multi-tier severity classification
- Automated notification mechanisms
- Role-specific escalation protocols

### Clinical Intelligence
- NIHSS Score Tracking
- Automated risk assessment
- Treatment recommendation support


- Real-time alerts and notifications
- HIPAA-compliant data storage
- Comprehensive patient records
- NHISS scoring system
- Medical imaging management
- Vital signs tracking

## Setup Instructions

1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up environment variables:
Create a `.env` file in the project root with the following variables:
```
DEBUG=True
SECRET_KEY=your-secret-key
DATABASE_URL=postgres://user:password@localhost:5432/dbname
```

4. Run migrations:
```bash
python manage.py migrate
```

5. Create a superuser:
```bash
python manage.py createsuperuser
```

6. Run the development server:
```bash
python manage.py runserver
```

## Project Structure

- `stroke_system/` - Main project configuration
- `patients/` - Patient management app
- `neurologists/` - Neurologist consultation app
- `alerts/` - Alert and notification system
- `api/` - REST API endpoints

## Security

This application follows HIPAA compliance guidelines and implements:
- Data encryption
- Access control
- Audit logging
- Secure authentication

## 📄 License

### MIT License

Copyright (c) 2025 MSUnit Project

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.

### Disclaimer
This software is for educational purposes and should not be used in actual
medical settings without proper validation and regulatory approval.

## 📞 Contact
- **Project Maintainer**: [Your Name]
- **Email**: your.email@example.com
- **Project Repository**: [GitHub Repository URL]

This project is licensed under the MIT License. 