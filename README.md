# Ansible Docker Deployment

## Overview

Automated Docker container deployment using Ansible playbooks. Pulled container images, deployed NGINX containers, and validated infrastructure automation workflows.

---

## Technologies

- Ansible
- Docker
- Linux
- YAML

---

## Architecture

```text
Ansible Playbook
      ↓
Docker Engine
      ↓
NGINX Container
```

---

## Commands Used

```bash
ansible-galaxy collection install community.docker

ansible-playbook -i inventory.ini deploy-docker.yml

docker ps

curl http://localhost:8085
```

---

## Screenshots

### Inventory File

![Inventory](screenshots/inventory-file.png)

### Playbook Configuration

![Playbook](screenshots/playbook-yaml.png)

### Playbook Execution

![Execution](screenshots/ansible-playbook-run.png)

### Running Container

![Docker](screenshots/docker-ps.png)

### Curl Validation

![Curl](screenshots/curl-validation.png)

### Browser Validation

![Browser](screenshots/browser-validation.png)

### Project Structure

![Structure](screenshots/project-structure.png)

---

## Key Outcomes

- Automated Docker deployment
- Used Ansible playbooks
- Managed containers through automation
- Validated infrastructure deployment
- Practiced configuration management