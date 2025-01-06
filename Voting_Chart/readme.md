# Django Data Chart Project

A Django web application that generates and displays interactive data charts using Chart.js. This project is designed for learning and demonstration purposes.

---

## Features
- Create, manage, and visualize datasets.
- Dynamic data visualization using Chart.js.
- User-friendly interface.
- Fully functional Django backend.

---

## Requirements

Ensure you have the following installed:

- Python (>=3.7)
- Django (>=4.0)
- pip (Python package manager)
- virtualenv (optional but recommended)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/django-data-chart.git
   cd django-data-chart
   ```

2. Create a virtual environment (optional):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Apply database migrations:
   ```bash
   python manage.py migrate
   ```

5. Start the development server:
   ```bash
   python manage.py runserver
   ```

6. Access the application at `http://127.0.0.1:8000/` in your web browser.

---

## Usage

1. Navigate to the dataset creation page to add or manage datasets.
2. View the charts on the visualization page.
3. Customize chart types and styles through the settings interface.

---

## Project Structure

```
.
├── charts                # Django app for handling chart data
├── static                # Static files (CSS, JS, images)
├── templates             # HTML templates
├── manage.py             # Django management script
├── db.sqlite3            # SQLite database file
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

---

## Key Files

- `charts/models.py`: Defines the data models.
- `charts/views.py`: Handles requests and renders templates.
- `charts/templates`: Contains HTML templates for the app.
- `static/js`: Includes Chart.js for rendering charts.

---

## Dependencies

- Django: Backend framework.
- Chart.js: For interactive data visualization.
- SQLite: Default database for development.

---

## Contribution

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add a new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Acknowledgements

- [Django Framework](https://www.djangoproject.com/)
- [Chart.js](https://www.chartjs.org/)

---

Happy coding!
