## Backend

Prerequisites
```sh
pip install pipenv
pipenv shell
pipenv install
```

Running
```sh
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

## Frontend

Prerequisites

```sh
npm install -g yarn
yarn add vite
yarn add vue
```

Running

```sh
cd frontend
yarn
yarn dev
```