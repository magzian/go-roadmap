# go-roadmap

Great! Here's a **4–6 week backend engineer learning roadmap** tailored to take you from “built a Pong game in Go” to “ready to apply for a high-paced backend role,” focusing on *Go, scalability, systems design, and DevOps*.

---

## 🚀 **Backend Engineer Roadmap (4–6 Weeks)**

> 📌 Daily time commitment: 2–3 hours recommended
> 🛠️ Format: Project-based + Reading + Practice
> 👨‍💻 Outcome: You’ll build and deploy a scalable backend project (with monitoring + database + CI/CD) to showcase in your portfolio.

---

### 🔹 **WEEK 1 – Backend Fundamentals & Real-World Go**

**Goal**: Transition from game dev mindset to scalable backend services in Go.

#### 🔧 What to Learn

* Web server basics: `net/http`, routing, middleware
* REST APIs: status codes, CRUD operations
* JSON handling
* Structuring Go projects (`cmd`, `pkg`, `internal`)

#### 📚 Resources

* [Go Web Examples](https://gowebexamples.com/)
* [Build a REST API with Go](https://tutorialedge.net/golang/go-rest-api-postgresql/)
* [Go Project Layout (GitHub)](https://github.com/golang-standards/project-layout)

#### ✅ Project Task

* Create a basic RESTful service in Go:

  * `/ping` returns “pong”
  * `/todos` supports `GET`, `POST`, `DELETE`
* Use PostgreSQL or SQLite to store data

---

### 🔹 **WEEK 2 – Databases & Persistence Layer**

**Goal**: Learn how to model and manage data, optimize queries, and interact with databases.

#### 🔧 What to Learn

* SQL basics: indexes, joins, constraints
* ORMs in Go: `GORM` or `sqlx`
* Migrations with `golang-migrate` or `goose`
* Transactions and ACID principles

#### 📚 Resources

* [SQLBolt](https://sqlbolt.com/)
* [GORM Tutorial](https://gorm.io/docs/index.html)
* [Use The Index, Luke](https://use-the-index-luke.com/)

#### ✅ Project Task

* Extend your API with:

  * Auth: Register/Login using JWT
  * Database-backed users & todos with migrations

---

### 🔹 **WEEK 3 – Concurrency, Caching & Real-Time**

**Goal**: Dive into Go’s killer feature: concurrency. Learn how real-time systems work.

#### 🔧 What to Learn

* Go routines, channels, mutexes
* Worker pools & fan-in/out patterns
* WebSockets for real-time updates
* Redis for caching (basic TTL)

#### 📚 Resources

* [Go Concurrency Patterns - Rob Pike (YouTube)](https://www.youtube.com/watch?v=f6kdp27TYZs)
* [Go by Example - Concurrency](https://gobyexample.com/)
* [Go WebSocket Example](https://github.com/gorilla/websocket)

#### ✅ Project Task

* Add a background task (e.g., email worker or data processor)
* Implement a WebSocket endpoint for real-time updates

---

### 🔹 **WEEK 4 – Deployment, CI/CD, Docker & Cloud**

**Goal**: Learn to containerize, test, and deploy your backend like a pro.

#### 🔧 What to Learn

* Dockerizing Go apps
* Docker Compose for local DB + backend
* CI/CD with GitHub Actions
* Deploy to Render, Railway, Fly.io, or DigitalOcean

#### 📚 Resources

* [Docker for Go Developers](https://earthly.dev/blog/golang-docker/)
* [CI/CD with GitHub Actions](https://docs.github.com/en/actions)
* [Fly.io Deployment Guide](https://fly.io/docs/)

#### ✅ Project Task

* Dockerize your full stack (backend + DB)
* Deploy your app publicly (include a README)
* Setup GitHub Actions to run tests and deploy on push

---

### 🔹 **WEEK 5 – Monitoring, Logging, Testing**

**Goal**: Make your app production-ready with logs, tests, and observability.

#### 🔧 What to Learn

* Unit testing with `testing` + `testify`
* Integration testing using `httptest`
* Logging with `zap` or `logrus`
* Monitoring with Prometheus & Grafana (basic setup)

#### 📚 Resources

* [Go Testing Tutorial](https://golang.org/pkg/testing/)
* [Prometheus Go Client](https://github.com/prometheus/client_golang)

#### ✅ Project Task

* Add tests for all API endpoints
* Add logs for major operations
* Setup basic Prometheus metrics (e.g., request count)

---

### 🔹 **WEEK 6 – System Design + Final Polish**

**Goal**: Learn how to talk about what you built like a real backend engineer.

#### 🔧 What to Learn

* System Design fundamentals: availability, consistency, scalability
* CAP theorem, load balancing, caching, queues
* Prepare a technical write-up of your project

#### 📚 Resources

* [System Design Primer (GitHub)](https://github.com/donnemartin/system-design-primer)
* \[Grokking System Design Interview (if available)]

#### ✅ Project Task

* Create an architecture diagram for your app
* Write a README that includes:

  * Problem it solves
  * API documentation
  * Architecture overview
  * Technologies used
* Record a 3–5 minute walkthrough (optional but powerful)

---

## 🧠 Final Tip: Showcase Your Work

* Deploy the project
* Push it to GitHub (clean commits, good structure)
* Link it in your resume or application
* Write a short blog post or Dev.to article about the biggest lessons you learned

---


