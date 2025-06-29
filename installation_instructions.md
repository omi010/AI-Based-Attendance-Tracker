# Installation Instructions

## Error Fix: Missing AllAuth Package

To fix the "ModuleNotFoundError: No module named 'allauth'" error, you need to install the django-allauth package. Please follow these steps:

1. Make sure your virtual environment is activated. If not, activate it using:
   ```
   venv\Scripts\activate   # On Windows
   source venv/bin/activate   # On macOS/Linux
   ```

2. Install the django-allauth package:
   ```
   pip install django-allauth==0.58.2
   ```

3. Verify the installation:
   ```
   pip list | grep allauth
   ```
   This should show "django-allauth 0.58.2" in the output.

4. Once the package is installed, you can start the Django development server:
   ```
   python manage.py runserver
   ```

## Additional Notes

- If you face issues with other packages, you can install all dependencies at once using:
  ```
  pip install -r requirements.txt
  ```

- Make sure you're using the correct Python environment. If you have multiple environments, ensure you're activating the one that contains your Django project.
