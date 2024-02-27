### Making migrations

When you change your Django models, the database itself doesn’t update. To make changes to the database schema, you need to create a migration.

1. Change your models (in models.py).
1. Run `python manage.py makemigrations` to create migrations for those changes
1. Run `python manage.py migrate to apply` those changes to the database.
