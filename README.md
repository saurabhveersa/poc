
---

## ✅ 1. `django-kube-app/README.md` (Python + Docker)

```markdown
# Django App: django-kube-app

This is the Python Django project for the Kubernetes-based scalable app. It supports REST APIs, subscription management, payments, and more.

---

## 📁 Project Structure

django-kube-app/
├── manage.py
├── requirements.txt
├── Dockerfile
├── django_kube_app/
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
└── api/
├── views.py
├── models.py
└── ...


---

## ⚙️ Features

- User login and signup
- Profile update
- Product browsing and detail view
- Monthly subscription
- Multiple payment options (UPI, Cards, Netbanking)
- REST API with Django Rest Framework
- Health checks for Kubernetes liveness/readiness probes

---

## 🐳 Docker Setup

### 🧪 Build Image

```bash
docker build -t django-kube-app .
```

## Run Locally

docker run -p 8000:8000 django-kube-app

Then open:

http://localhost:8000/api/management/?format=api


