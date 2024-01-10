<!-- packages installed -->
Django
djangorestframework==3.14.0
python-dotenv-1.0.0
pytest==7.4.3
pytest-django==4.7.0
django-mptt-0.15.0
drf-spectacularr-0.27.0
coverage

<!-- cmds -->
from django.core.management.utils import get_random_secret_key
print(get_random_secret_key())
coverage run -m pytest
pytest --cov