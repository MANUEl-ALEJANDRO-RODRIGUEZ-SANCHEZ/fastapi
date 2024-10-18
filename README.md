# 🚀 FastAPI: List of Names 👥

Welcome to this simple yet powerful API project using **FastAPI** in Python! 🎉 Here we will show you how to build and run an API that returns a list of names with just a few steps.

## 🌟 Objective

The goal of this project is to show how you can create a basic **API** with **FastAPI** in Python to expose an endpoint that returns a list of names. Simple, right? 😎

## 🛠️ Installation

### Requirements
- **Python 3.7+**
- **FastAPI**
- **Uvicorn**

If you don't have **FastAPI** and **Uvicorn**, install them by running the following command in your terminal:

```bash
pip install fastapi uvicorn
```

### How to run the application:

To get the API up and running, run the following command in your terminal:

```bash
uvicorn main:app --reload
```

Boom! 🚀 Your API is running at `http://127.0.0.1:8000` 🎉

## 📄 Endpoints

### 🔍 `GET /names`

This endpoint returns a simple list with a few names:

```json
["John", "Maria", "Pedro"]
```

### 🧠 Code Explanation

1. **FastAPI**: We use the `FastAPI()` class to create our application.
2. **@app.get("/names")**: This decorator defines an endpoint for the `/names` route that responds to `GET` requests.
3. **get_names**: This function is asynchronous and returns a list with three names when someone calls the endpoint.
4. **Uvicorn**: We use `uvicorn` to spin up the server on port `8000`.

## ✨ Why FastAPI?

**FastAPI** is amazing for several reasons:
- **Easy to use**: You can get started quickly, even if you're new to API development.
- **Fast and efficient**: Built on Starlette and Pydantic, making it extremely fast. ⚡
- **Great documentation**: Guides you through every step so you don't get lost. 📚
- **Automatically generates documentation**: Yes, you can view your API documentation in `/docs` or `/redoc`!

## 📚 Additional resources:

- [Official FastAPI documentation](https://fastapi.tiangolo.com/)
- [FastAPI tutorials](https://fastapi.tiangolo.com/tutorial/)

## Author

### Manuel Rodriguez
