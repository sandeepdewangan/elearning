## eLeaning

### Fixtures
Fixtures are used to provide initial data for models. Loading and Dumping data from the database into files that are called fixtures.
Django supports JSON, XML, YAML formats.

Dumping data - (from db to file):\
`python manage.py dumpdata courses --indent=2`\
`mkdir courses/fixtures`\
`python manage.py dumpdata courses --indent=2 --output=courses/fixtures/subjects.json`

Loading data - (from file to db):\
`python manage.py loaddata courses/fixtures/subjects.json`