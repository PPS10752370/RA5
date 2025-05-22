# RA5 - Proyecto DevOps

Este repositorio está dividido en dos partes principales, organizadas en carpetas:

## 📁 RA5.1 - Calculadora con CI/CD

Contiene una calculadora en Python y su infraestructura de despliegue con:

- `Dockerfile`, `docker-compose.yml`
- `Jenkinsfile` y `Jenkinsfile.docker` para CI/CD
- `calculadora.py`, `test_calculadora.py`, `requirements.txt`

---

## 📁 RA5.2 - VM Ubuntu provisionada con Ansible

Contiene un entorno automatizado que:

- Lanza una máquina virtual Ubuntu (22.04) con Vagrant y VirtualBox
- Utiliza Ansible para:
  - Actualizar el sistema
  - Instalar Apache
  - Crear un `index.html` con el texto `Ansible rocks`
  - Verificarlo con `curl`

---

## 🛠️ Requisitos

- Python 3
- Docker
- Jenkins
- Vagrant
- VirtualBox
- Ansible

---

## 📌 Autor

Proyecto desarrollado por [Alex Rosell].
