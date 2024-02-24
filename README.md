# Full Stack FastAPI and PostgreSQL - Base Project Generator


Some of the future new features:

* Upgrade to the latest FastAPI.
* Migration from SQLAlchemy to SQLModel.
* Upgrade to Pydantic v2.
* Refactor and simplification of most of the code, a lot of the complexity won't be necessary anymore.
* Migrate from Vue.js 2 to React with hooks and TypeScript.
* Move from Docker Swarm Model to Kubernetes.
* GitHub Actions for CI.

---

Generate a backend and frontend stack using Python, including interactive API documentation.

### Interactive API documentation

![1](https://github.com/PranavPatil7/BasePrjGen/assets/30521517/954dccde-6d3d-4277-ae3e-9c8571837184)

### Alternative API documentation

![2](https://github.com/PranavPatil7/BasePrjGen/assets/30521517/b1e10cd4-6c62-4346-83bc-ea6d0e0d9a65)

### Dashboard Login

![3](https://github.com/PranavPatil7/BasePrjGen/assets/30521517/32a9100a-1062-403e-a2ee-86114e83fb0c)


### Dashboard - Create User

![4](https://github.com/PranavPatil7/BasePrjGen/assets/30521517/8ebcecca-2dcb-46de-8b57-8f7e13495521)


## Features

* Full **Docker** integration (Docker based).
* Docker Swarm Mode deployment.
* **Docker Compose** integration and optimization for local development.
* **Production ready** Python web server using Uvicorn and Gunicorn.
* Python <a href="https://github.com/tiangolo/fastapi" class="external-link" target="_blank">**FastAPI**</a>.
* **JWT token** authentication.
* **SQLAlchemy** models (independent of Flask extensions, so they can be used with Celery workers directly).
* Basic starting models for users (modify and remove as you need).
* **Alembic** migrations.
* **CORS** (Cross Origin Resource Sharing).
* **Celery** worker that can import and use models and code from the rest of the backend selectively.
* REST backend tests based on **Pytest**, integrated with Docker, so you can test the full API interaction, independent on the database. As it runs in Docker, it can build a new data store from scratch each time (so you can use ElasticSearch, MongoDB, CouchDB, or whatever you want, and just test that the API works).
* Easy Python integration with **Jupyter Kernels** for remote or in-Docker development with extensions like Atom Hydrogen or Visual Studio Code Jupyter.
* **Vue FrontEnd**.
* **PGAdmin** for PostgreSQL database, you can modify it to use PHPMyAdmin and MySQL easily.
* **Flower** for Celery jobs monitoring.
* Load balancing between frontend and backend with **Traefik**, so you can have both under the same domain, separated by path, but served by different containers.
* Traefik integration, including Let's Encrypt **HTTPS** certificates automatic generation.
* GitLab **CI** (continuous integration), including frontend and backend testing.


