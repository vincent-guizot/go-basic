# 🚀 Go Roadmap (for 5+ YOE Full Stack Dev)

This is a fast-track, hands-on roadmap to learn Go in **2 weeks** — focused on building and Dockerizing a RESTful API with Postgres.

---

## 🔹 PHASE 1: Go Language Basics (Day 1–2)

### ✅ Learn the Core Language
- [Tour of Go – Official](https://go.dev/tour/)
- [Go by Example](https://gobyexample.com/)
- [Go Syntax Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet)
- [Effective Go – Best Practices](https://go.dev/doc/effective_go)

### 🛠️ Exercises
- [ ] Setup Go with `go mod init`, `go run`, `go build`
- [ ] Create CLI app (e.g., calculator)
- [ ] Use structs, slices, maps, interfaces
- [ ] Handle errors idiomatically (`if err != nil`)
- [ ] Explore goroutines + channels (intro only)

---

## 🔹 PHASE 2: REST API with Gin (Day 3–5)

### ✅ Learn Gin & Project Structure
- [Gin Web Framework](https://github.com/gin-gonic/gin)
- [Gin Crash Course – YouTube](https://www.youtube.com/watch?v=JieYt7kCkVU)
- [MVC Project Structure Example](https://github.com/adiatma/go-rest-api)

### 🛠️ Exercises
- [ ] Build basic REST API (GET, POST, PUT, DELETE)
- [ ] Create folder structure:
  - `main.go`, `routes/`, `controllers/`, `models/`
- [ ] Use middlewares (logger, error handler)
- [ ] Return JSON responses with proper status codes

---

## 🔹 PHASE 3: Postgres + GORM (Day 6–8)

### ✅ Learn GORM + DB Integration
- [GORM Official Docs](https://gorm.io/)
- [GORM CRUD Example](https://gorm.io/docs/create.html)
- [Postgres with Docker](https://hub.docker.com/_/postgres)

### 🛠️ Exercises
- [ ] Set up Postgres with Docker or local
- [ ] Connect using GORM
- [ ] Define models + relations (1:N, N:M)
- [ ] Auto-migrate schemas
- [ ] Handle DB errors, return proper messages

---

## 🔹 PHASE 4: Config, Testing, Docker (Day 9–12)

### ✅ Learn Practical Dev Usage
- [godotenv – Env Config](https://github.com/joho/godotenv)
- [Go `testing` Package](https://go.dev/doc/tutorial/add-a-test)
- [Go Dockerfile Tutorial](https://docs.docker.com/language/golang/)

### 🛠️ Exercises
- [ ] Load `.env` for DB + PORT
- [ ] Write unit test for controller or service
- [ ] Build Dockerfile (multi-stage)
- [ ] Create `docker-compose.yml` with Go + Postgres
- [ ] Health check endpoint

---

## 🔹 PHASE 5: Bonus – Microservices, Deploy, Kafka (Day 13–14)

### ✅ Optional but Valuable
- [Kafka + Go with Sarama](https://github.com/Shopify/sarama)
- [Deploy with Railway](https://railway.app/)
- [Go Fiber – Fast Alternative to Gin](https://gofiber.io/)

### 🛠️ Exercises
- [ ] Add Kafka producer or consumer
- [ ] Deploy to Railway or VPS
- [ ] Try Go Fiber vs Gin
- [ ] Add Swagger docs (with [swaggo](https://github.com/swaggo/swag))

---

## ✅ Summary Checklist

| Task                                      | Done |
|-------------------------------------------|------|
| Go language fundamentals                  | [ ]  |
| REST API with Gin                         | [ ]  |
| Postgres integration with GORM            | [ ]  |
| Middleware, JSON handling                 | [ ]  |
| Env config + `.env` file                  | [ ]  |
| Unit testing                              | [ ]  |
| Dockerfile + docker-compose               | [ ]  |
| Health check + error handling             | [ ]  |
| Deployed to Railway or VPS                | [ ]  |
| Kafka producer/consumer (bonus)           | [ ]  |

---

_💡 Tip: Publish your API and document your code on GitHub — it becomes a Go portfolio for jobs or freelance._

