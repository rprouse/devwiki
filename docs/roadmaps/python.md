# :simple-python: Python Developer Roadmap
## Legend
- 🟢 Must Know
- 🔵 Good to Know
- 🟣 Alternative
- ⛔ Not Recommended

## Required Developer Skills
### Version Control
- 🟢 [Git](https://git-scm.com/)
- 🟢 [GitHub](https://github.com/)
- 🟣 [GitLab](https://gitlab.com/)
### Python
- 🟢 Python 3.9+
    - **Basic Syntax**: Variables, control flow (if, else, for, while), functions, classes.
    - **Advanced Features**: List comprehensions, generator expressions, decorators, context managers, async/await for asynchronous programming.
    - **Error Handling**: Exception handling with try, except, finally.
    - **Data Types**: Understanding mutable vs immutable types, using collections (list, tuple, dict, set), and typing for static type checks.
- 🟢 [Pip](https://pypi.org/project/pip/) (Python Package Installer)
- 🟢 [Virtual Environments](https://docs.python.org/3/tutorial/venv.html) (venv, virtualenv)
- 🔵 [Poetry](https://python-poetry.org/) for dependency management and packaging
### Web Development
- 🟢 [Flask](https://flask.palletsprojects.com/)
    - Flask RESTful APIs
    - Jinja templating
- 🟢 [Django](https://www.djangoproject.com/)
    - Django ORM
    - Django Templates
    - Django REST Framework for APIs
- 🔵 [FastAPI](https://fastapi.tiangolo.com/) for asynchronous web applications
### Data Science & Machine Learning
- 🟢 [NumPy](https://numpy.org/) for numerical computing
- 🟢 [Pandas](https://pandas.pydata.org/) for data manipulation and analysis
- 🟢 [Matplotlib](https://matplotlib.org/) / [Seaborn](https://seaborn.pydata.org/) for data visualization
- 🟢 [Scikit-learn](https://scikit-learn.org/stable/) for machine learning
- 🟢 [TensorFlow](https://www.tensorflow.org/) / [PyTorch](https://pytorch.org/) for deep learning
### Testing
- 🟢 [Pytest](https://docs.pytest.org/en/latest/)
- 🟢 [unittest](https://docs.python.org/3/library/unittest.html) (Python's standard library)
- Mocking
    - 🟢 [unittest.mock](https://docs.python.org/3/library/unittest.mock.html)
    - 🟢 [pytest-mock](https://pytest-mock.readthedocs.io/en/latest/)
### Databases
- 🟢 SQL Databases
    - 🟢 [SQLite](https://www.sqlite.org/index.html) (good for development and small projects)
    - 🟢 [PostgreSQL](https://www.postgresql.org/) with [Psycopg2](https://www.psycopg.org/) or [SQLAlchemy](https://www.sqlalchemy.org/)
- 🟢 NoSQL Databases
    - 🟢 [MongoDB](https://www.mongodb.com/) with [PyMongo](https://pymongo.readthedocs.io/en/stable/)
    - 🟢 [Redis](https://redis.io/) with [redis-py](https://github.com/redis/redis-py)
### ORM/ODM
- 🟢 [SQLAlchemy](https://www.sqlalchemy.org/) for SQL databases
- 🟢 [Django ORM](https://docs.djangoproject.com/en/3.2/topics/db/models/) (when using Django)
- 🟣 [Peewee](http://docs.peewee-orm.com/en/latest/)
- 🟣 [MongoEngine](http://mongoengine.org/) for MongoDB
### Asynchronous Programming
- 🟢 [asyncio](https://docs.python.org/3/library/asyncio.html) (Python's standard library for asynchronous I/O)
- 🟢 [aiohttp](https://docs.aiohttp.org/en/stable/) for asynchronous HTTP client/server
### Containers & Virtualization
- 🟢 [Docker](https://www.docker.com/)
- Orchestration
    - 🟢 [Kubernetes](https://kubernetes.io/)
- Tooling
    - 🟣 [Docker Compose](https://docs.docker.com/compose/) for multi-container Docker applications
### CI/CD & Automation
- 🟢 [GitHub Actions](https://github.com/features/actions)
- 🟣 [GitLab CI/CD](https://docs.gitlab.com/ee/ci/)
- 🟣 Jenkins

Jenkins](https://www.jenkins.io/)
### Cloud Services
- 🟢 AWS (Amazon Web Services)
- 🟢 GCP (Google Cloud Platform)
- 🟢 Azure
- Serverless
    - 🟢 AWS Lambda
    - 🟢 Azure Functions
    - 🟢 Google Cloud Functions
### DevOps Tools
- Infrastructure as Code
    - 🟢 [Terraform](https://www.terraform.io/)
    - 🔵 [Ansible](https://www.ansible.com/)
### Python Libraries and Frameworks
- 🟢 [Requests](https://requests.readthedocs.io/en/master/) for HTTP requests
- 🟢 [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/) / [Scrapy](https://scrapy.org/) for web scraping
- 🟢 [Pillow](https://python-pillow.org/) for image processing

This roadmap focuses on Python's versatility across web development, data science, machine learning, automation, and more, providing a broad spectrum of technologies that a Python developer may want to become proficient in.