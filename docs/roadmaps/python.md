# :simple-python: Python Developer Roadmap

!!! info "Legend"
    :green_heart: Must Know
    :material-emoticon-excited-outline:{ .good_to_know } Good to Know
    :material-lightning-bolt:{ .alternative } Alternative
    :no_entry: Not Recommended

## Version Control

- :green_heart: [Git](https://git-scm.com/)
- :green_heart: [GitHub](https://github.com/)
- :material-lightning-bolt:{ .alternative } [GitLab](https://gitlab.com/)
- :no_entry: Mercurial
- :no_entry: SVN/Subversion

## Python

- :green_heart: Python 3.9+
    - **Basic Syntax**: Variables, control flow (if, else, for, while), functions, classes.
    - **Advanced Features**: List comprehensions, generator expressions, decorators, context managers, async/await for asynchronous programming.
    - **Error Handling**: Exception handling with try, except, finally.
    - **Data Types**: Understanding mutable vs immutable types, using collections (list, tuple, dict, set), and typing for static type checks.
- :green_heart: [Pip](https://pypi.org/project/pip/) (Python Package Installer)
- :green_heart: [Virtual Environments](https://docs.python.org/3/tutorial/venv.html) (venv, virtualenv)
- :material-emoticon-excited-outline:{ .good_to_know } [Poetry](https://python-poetry.org/) for dependency management and packaging

## Web Development

- :green_heart: [Flask](https://flask.palletsprojects.com/)
    - Flask RESTful APIs
    - Jinja templating
- :green_heart: [Django](https://www.djangoproject.com/)
    - Django ORM
    - Django Templates
    - Django REST Framework for APIs
- :material-emoticon-excited-outline:{ .good_to_know } [FastAPI](https://fastapi.tiangolo.com/) for asynchronous web applications

## Data Science & Machine Learning

- :green_heart: [NumPy](https://numpy.org/) for numerical computing
- :green_heart: [Pandas](https://pandas.pydata.org/) for data manipulation and analysis
- :green_heart: [Matplotlib](https://matplotlib.org/) / [Seaborn](https://seaborn.pydata.org/) for data visualization
- :green_heart: [Scikit-learn](https://scikit-learn.org/stable/) for machine learning
- :green_heart: [TensorFlow](https://www.tensorflow.org/) / [PyTorch](https://pytorch.org/) for deep learning

## Testing

- :green_heart: [Pytest](https://docs.pytest.org/en/latest/)
- :green_heart: [unittest](https://docs.python.org/3/library/unittest.html) (Python's standard library)
- Mocking
    - :green_heart: [unittest.mock](https://docs.python.org/3/library/unittest.mock.html)
    - :green_heart: [pytest-mock](https://pytest-mock.readthedocs.io/en/latest/)

## Databases

- :green_heart: SQL Databases
    - :green_heart: [SQLite](https://www.sqlite.org/index.html) (good for development and small projects)
    - :green_heart: [PostgreSQL](https://www.postgresql.org/) with [Psycopg2](https://www.psycopg.org/) or [SQLAlchemy](https://www.sqlalchemy.org/)
- :green_heart: NoSQL Databases
    - :green_heart: [MongoDB](https://www.mongodb.com/) with [PyMongo](https://pymongo.readthedocs.io/en/stable/)
    - :green_heart: [Redis](https://redis.io/) with [redis-py](https://github.com/redis/redis-py)

## ORM/ODM

- :green_heart: [SQLAlchemy](https://www.sqlalchemy.org/) for SQL databases
- :green_heart: [Django ORM](https://docs.djangoproject.com/en/3.2/topics/db/models/) (when using Django)
- :material-lightning-bolt:{ .alternative } [Peewee](http://docs.peewee-orm.com/en/latest/)
- :material-lightning-bolt:{ .alternative } [MongoEngine](http://mongoengine.org/) for MongoDB

## Asynchronous Programming

- :green_heart: [asyncio](https://docs.python.org/3/library/asyncio.html) (Python's standard library for asynchronous I/O)
- :green_heart: [aiohttp](https://docs.aiohttp.org/en/stable/) for asynchronous HTTP client/server

## Containers & Virtualization

- :green_heart: [Docker](https://www.docker.com/)
- Orchestration
    - :green_heart: [Kubernetes](https://kubernetes.io/)
- Tooling
    - :material-lightning-bolt:{ .alternative } [Docker Compose](https://docs.docker.com/compose/) for multi-container Docker applications

## CI/CD & Automation

- :green_heart: [GitHub Actions](https://github.com/features/actions)
- :material-lightning-bolt:{ .alternative } [GitLab CI/CD](https://docs.gitlab.com/ee/ci/)
- :material-lightning-bolt:{ .alternative } Jenkins

Jenkins](<https://www.jenkins.io/>)

## Cloud Services

- :green_heart: AWS (Amazon Web Services)
- :green_heart: GCP (Google Cloud Platform)
- :green_heart: Azure
- Serverless
    - :green_heart: AWS Lambda
    - :green_heart: Azure Functions
    - :green_heart: Google Cloud Functions

## DevOps Tools

- Infrastructure as Code
    - :green_heart: [Terraform](https://www.terraform.io/)
    - :material-emoticon-excited-outline:{ .good_to_know } [Ansible](https://www.ansible.com/)

## Python Libraries and Frameworks

- :green_heart: [Requests](https://requests.readthedocs.io/en/master/) for HTTP requests
- :green_heart: [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/) / [Scrapy](https://scrapy.org/) for web scraping
- :green_heart: [Pillow](https://python-pillow.org/) for image processing

This roadmap focuses on Python's versatility across web development, data science, machine learning, automation, and more, providing a broad spectrum of technologies that a Python developer may want to become proficient in.
