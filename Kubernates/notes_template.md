

### ☸️ Kubernetes Lab Template (`Kubernetes/notes_template.md`)

```markdown
# ☸️ Kubernetes Lab: [Topic Name]

## 📝 Overview
* **Date:** 2026-02-13
* **Objective:** (e.g., Setting up a LoadBalancer Service)
* **Status:** 🟢 Completed / 🟡 In-Progress

---

## 📄 Manifests (YAML)
```yaml
# Paste your Deployment or Service YAML here

```

## ⌨️ Essential Commands

* **Apply:** `kubectl apply -f filename.yaml`
* **Status:** `kubectl get all`
* **Debug:** `kubectl describe pod [name]`
* **Logs:** `kubectl logs -f [name]`

---

## 💡 Notes & Lessons

* (e.g., Learned how selectors link Services to Deployments.)

```

---

### 🐋 Docker Cheat Sheet (`Docker/cheat_sheet.md`)
| Action | Command |
| :--- | :--- |
| **Build Image** | `docker build -t name:tag .` |
| **Run Container** | `docker run -d --name my-app -p 80:80 name:tag` |
| **List Running** | `docker ps` |
| **Stop All** | `docker stop $(docker ps -q)` |
| **View Logs** | `docker logs -f [container_id]` |
| **Shell Access** | `docker exec -it [container_id] sh` |
| **Remove Image** | `docker rmi [image_id]` |

You can now copy these into your local folders to keep your Cloud Learning documentation consistent!
http://googleusercontent.com/action_card_content/1

```