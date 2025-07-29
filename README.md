# Module 12
---


## My DockerHub Image
[Visit the DockerHub Page](https://hub.docker.com/r/pruthvidholkia/is601_module13_assignment)


---


## Home Page

![Github action](/screenshots/home.png)


---


## User Registration

![Github action](/screenshots/register.png)


---


## User login and Dashboard

![Github action](/screenshots/dashboard.png)


---


## Running Tests Locally

Make sure your virtual environment is activated and dependencies installed.


```bash
python3 -m venv venv

source venv/bin/activate
```

---


### Install Dependencies

```bash
pip install -r requirements.txt
```

---


## Clone the Repository
```bash
git clone https://github.com/pruthvidholakia/is601_assignment13

cd is601_assignment13
```


---


## Create & Activate Virtual Environment
```bash
python3 -m venv venv

source venv/bin/activate  # On Windows: venv\Scripts\activate
```


---


## Install Dependencies

```bash
pip install -r requirements.txt
```


---


## Run All Tests

```bash
pytest
```


---


## Build Docker Image

```bash
docker build -t <image-name> .
```

---


## Run Docker Container
```bash
docker run -it --rm <image-name>
```

