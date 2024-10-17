# EHR - Malcolm's Anatomy

### A Comprehensive Electronic Health Records System for Low-Resource Clinics in Nigeria

## Project Overview
EHR - Malcolm's Anatomy is an open-source Electronic Health Records (EHR) system designed specifically to meet the needs of low-resource clinics and health centers in Nigeria and other developing regions. This project focuses on providing healthcare institutions with an easy-to-use, secure, and offline-capable solution to manage patient data, track appointments, and access medical histories without the need for constant internet access.

This project is maintained and developed by **Malcolm's Anatomy**, with the aim to improve healthcare delivery through the application of technology in the health sector.

---

## Features

- **Patient Management**: Add, view, update, and delete patient records (name, age, address, medical history, etc.).
- **Appointment Scheduling**: Track and manage patient appointments.
- **Offline Functionality**: Data can be stored locally and synced to the cloud when the internet is available.
- **Role-Based Access Control**: Different levels of access for doctors, nurses, and administrators.
- **Secure Data Storage**: Data is securely stored and encrypted to maintain patient confidentiality.
- **Scalable**: Initially designed for single clinics, but can be extended to multi-clinic setups.

---

## Project Structure

```plaintext
EHR-Malcolms-Anatomy/
│
├── ehr/                    # Main Django/Flask project directory
│   ├── settings.py         # Project settings (Django-specific)
│   ├── urls.py             # URL routing for the project
│   └── wsgi.py             # WSGI application for deployment
├── patients/               # Patient management app/module
│   ├── models.py           # Database models (Patient, Appointment, etc.)
│   ├── views.py            # Views for handling HTTP requests
│   ├── forms.py            # Forms for patient data input
│   └── urls.py             # URL routing for patients module
├── static/                 # Static files (CSS, JavaScript, images)
├── templates/              # HTML templates for the project
│
├── manage.py               # Command-line utility for Django/Flask
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## Usage

1. **Patient Registration**:
Navigate to the patient registration page.
Fill out the form with the patient’s details (name, age, medical history, etc.).
Submit the form to save the patient record.

2. **Appointment Scheduling**:
Visit the appointment scheduling page.
Choose the patient, date, and time of the appointment.
Submit to record the appointment.

3. **Offline Mode**:
The system works offline by storing patient records in local storage.
Once the connection is restored, the data will automatically sync with the cloud (this feature will be added in later phases).

---

## Contributing

We welcome contributions to EHR - Malcolm's Anatomy. Here's how you can help:
```bash

Fork the repository.
Create a branch for your feature (git checkout -b feature/amazing-feature).
Commit your changes (git commit -m 'Add some amazing feature').
Push to the branch (git push origin feature/amazing-feature).
Open a Pull Request to discuss your changes.
```

---

## Project Roadmap

### Phase 1 - MVP (Minimum Viable Product)
```plaintext
Patient registration and management
Appointment scheduling
Offline functionality (local storage)
```
### Phase 2 - Enhanced Functionality
```plaintext
User authentication and role-based access
Data encryption for sensitive information
Cloud sync and data backup
```
### Phase 3 - Advanced Features
```plaintext
Multi-clinic setup with a central database
Analytics dashboard for tracking patient health metrics
Integration with third-party medical services (labs, pharmacies, etc.)
```

---

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

---

## Contact

For any questions or support, please reach out via:

Email: admin@malcolmsanatomy.com.ng
Website: www.malcolmsanatomy.com.ng
