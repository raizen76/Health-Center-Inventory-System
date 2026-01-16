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
