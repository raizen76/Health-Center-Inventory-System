**Health Center Inventory System**
  - A robust inventory management system specifically designed for health centers and medical facilities. Features comprehensive tracking of medical supplies, medicines, and equipment with role-based access control.

**Key Features**
  1. Role-Based Access Control
    - Multi-level user authentication and authorization system ensuring secure access to sensitive medical inventory data.
  2. Dashboard & Monitoring
    - Real-time overview of inventory status, stock levels, and system activities with intuitive data visualization.
  3. Inventory Management
    - Complete tracking system for medical supplies, medicines, and equipment with automated low-stock alerts.
  4. Medicine Request Management
    - Streamlined process for requesting and approving medicine requisitions with approval workflows.
  5. Borrowed Item Tracking
    - Monitor borrowed medical equipment and supplies with return date tracking and reminders.
  6. Reports & Logs
    - Generate comprehensive reports on inventory usage, transaction history, and system audit logs.
  7. User Verification
    - Secure user authentication system with verification processes for authorized personnel only.

**Technologies Used**

- **Backend Framework:** Django 6.0
- **Database:** MySQL
- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap 5
- **Authentication:** Django Authentication System
- **Additional Libraries:** Django REST Framework, Chart.js

## System Requirements

- Python 3.8+
- MySQL 8.0+
- pip (Python package manager)

## Installation Guide

1. **Clone the repository**
```bash
git clone https://github.com/raizen76/health-center-inventory-system.git
cd health-center-inventory-system

2. **Set up virtual environment**

python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Configure database**
Create a MySQL database and update `settings.py`:
```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'bhms_db',
        'USER': 'root',
        'PASSWORD': 'jansen123',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}
```

5. **Run migrations**
```bash
python manage.py makemigrations
python manage.py migrate
```

6. **Create superuser account**
```bash
python manage.py createsuperuser
```

7. **Start development server**
```bash
python manage.py runserver
```

8. **Access the application**
Navigate to `http://localhost:8000` in your web browser.

## User Roles

- **Administrator** - Full system access and user management
- **Health Staff** - View inventory and submit requests
- **Viewer** - Read-only access to reports

## Screenshots

  **ADMINISTRATOR**
<img width="1919" height="909" alt="image" src="https://github.com/user-attachments/assets/dfa1e578-922e-48e0-a384-a206b6749425" />
<img width="1918" height="909" alt="image" src="https://github.com/user-attachments/assets/7966389b-fde5-48d8-bedd-2e35e9d03fb9" />
<img width="1911" height="909" alt="image" src="https://github.com/user-attachments/assets/413fba6e-4842-429d-93ef-1da012d27aa2" />
<img width="1913" height="908" alt="image" src="https://github.com/user-attachments/assets/f30d5023-85dd-4cd5-a1e0-cc8442580718" />

 **Health Staff**
<img width="1896" height="911" alt="image" src="https://github.com/user-attachments/assets/736b179d-ebd5-46d5-873a-856f13007fc6" />
<img width="1919" height="919" alt="image" src="https://github.com/user-attachments/assets/1aabbbe5-d207-4546-87e8-665ffdf71158" />
<img width="1919" height="915" alt="image" src="https://github.com/user-attachments/assets/e627fa46-f042-4b33-bccb-49aa39f28893" />
<img width="1918" height="918" alt="image" src="https://github.com/user-attachments/assets/4a542a4a-7d41-434c-b78f-1853a1f40305" />
<img width="1911" height="917" alt="image" src="https://github.com/user-attachments/assets/cd74ecf1-f462-46e5-b2ef-669ad84ff881" />
<img width="1919" height="907" alt="image" src="https://github.com/user-attachments/assets/2a4ef2d7-0bf1-4738-9806-b897167c524e" />

**Viewer**
<img width="1918" height="907" alt="image" src="https://github.com/user-attachments/assets/bf11c39b-82e0-4430-a340-f37906969bd6" />
<img width="1897" height="907" alt="image" src="https://github.com/user-attachments/assets/bccbd7de-54e9-4b8e-bef0-c8f6eaf67d6a" />
<img width="1919" height="874" alt="image" src="https://github.com/user-attachments/assets/c895916d-6705-4dde-b95b-978da7174dab" />
<img width="1635" height="907" alt="image" src="https://github.com/user-attachments/assets/b8b80ba7-5536-404c-aa13-3fb614ba1a3f" />
<img width="1886" height="908" alt="image" src="https://github.com/user-attachments/assets/0bc0daf9-c474-449b-b306-ae49e3daf8b8" />
<img width="1886" height="908" alt="image" src="https://github.com/user-attachments/assets/425fb52e-8070-4769-8581-c3abae32b849" />

## Future Development

- [ ] Integration with hospital management systems
- [ ] Mobile application for inventory scanning
- [ ] Automated reordering system
- [ ] Expiry date tracking and alerts
- [ ] Barcode/QR code scanning


## Author

Jansen Stephen M. Delos Reyes 
Computer Engineering Student, 3rd Year  
GitHub - https://github.com/raizen76
