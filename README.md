# Django-Admin-Interface
personnaliser son admin Django



# Etape 1 :   Installation

      pip install django-admin-interface

# Etape 2 : Dans le settings.py

      INSTALLED_APPS  = (
          ' admin_interface ' ,
          ' flat_responsive ' ,
          ' flat ' ,
          ' colorfield ' ,
          ' django.contrib.admin ' ,
          ... 
      )

# Etape 3 : Migration

      python manage.py migrate
      python manage.py collectstatic

# Etape 4 : Quelques themes

      python manage.py loaddata admin_interface_theme_django.json
      python manage.py loaddata admin_interface_theme_bootstrap.json
      python manage.py loaddata admin_interface_theme_foundation.json
      python manage.py loaddata admin_interface_theme_uswds.json
