# How to Learn Golang

Golang is a *boring* language — and that’s a compliment. It’s simple, fast, and pragmatic. It may not wow you with clever syntax tricks, but it's a great choice for building real-world software, business applications, and scalable backend services.

This guide aims to provide a practical and honest approach to learning Golang (also known as Go). There's no single "right" way to learn a programming language. Instead, I'll outline several paths to help you choose what best fits your style, background, and goals.

## 1. Getting Started with Go

### 1.1. Official Resources

The official [Go website](https://go.dev/) is one of the best starting points. It includes:

- [The Go Tour](https://go.dev/tour): A guided introduction to Go, with interactive code snippets  
- [Documentation](https://go.dev/doc/): Well-written and to the point  
- [Blog](https://go.dev/blog/): Updates and best practices from the Go team
- [Learn](https://go.dev/learn/): A section of resources, many of which are also featured in this article.

---

### 1.2. Online Courses

[Class Central](https://www.classcentral.com/subject/golang) lists over 100 Go courses. Here are some notable options:

- [Programming with Google Go Specialization](https://www.coursera.org/specializations/google-golang) by Ian G. Harris (UC Irvine). One of the longest-standing and most reputable Go courses.
- [Go: The Complete Developer's Guide](https://www.udemy.com/course/go-the-complete-developers-guide/). Highly rated on Udemy, with comprehensive content.
- [Learn How To Code: Google's Go Programming Language](https://www.udemy.com/course/learn-how-to-code/). Very practical and exercise-focused.

---

### 1.3. Books

When it comes to books, I rely entirely on the Go team's recommended reading list:

- [*The Go Programming Language*](https://www.goodreads.com/book/show/25080953-the-go-programming-language) — Alan A. A. Donovan & Brian W. Kernighan  
- [*Concurrency in Go*](https://www.goodreads.com/book/show/30413199-concurrency-in-go) — Katherine Cox-Buday  
- [*Introducing Go*](https://www.goodreads.com/book/show/27015358-introducing-go) — Caleb Doxsey

---

### 1.4. Learn by Doing

---

#### Learn by Example

If you prefer learning by reading code, start with the concise [Learn X in Y Minutes (Go)](https://learnxinyminutes.com/docs/go/) for a quick syntax overview, or dive into [Go by Example](https://gobyexample.com/) — a more detailed and practical guide now officially recommended on the Go website.

---

#### Learn by Practice

Writing Go code is the best way to learn.

[Exercism](https://exercism.org/tracks/go) is a highly recommended platform in the Gophers Slack community.  
However, it doesn't always cover the basics in depth, so it’s useful to combine it with books or tutorials.

Another fantastic resource is [Learn Go with Tests](https://quii.gitbook.io/learn-go-with-tests). It takes a [test-driven development (TDD)](https://en.wikipedia.org/wiki/Test-driven_development) approach, helping you build a solid understanding of Go by writing unit tests from the start. It’s a great way to learn both the language and good engineering practices.

---

### 1.5. Join the Community

Connecting with others can accelerate your learning. Try:

- [Gophers Slack](https://invite.slack.golangbridge.org/)
- [r/golang](https://www.reddit.com/r/golang/) on Reddit

---

## 2. Core Knowledge & Style

### 2.1. Articles & Best Practices

There are countless articles about Go, but a few stand out as must-reads:
- [Effective Go](https://go.dev/doc/effective_go) — This is the cornerstone of idiomatic Go. It’s referenced throughout the ecosystem and is essential for writing clean, idiomatic code.
- [Practical Go: Real world advice for writing maintainable Go programs](https://dave.cheney.net/practical-go/presentations/gophercon-singapore-2019.html) — Written by Dave Cheney, a well-known figure in the Go community, this article (and talk) offers valuable tips.
- [Go Wiki](https://go.dev/wiki/) — A central hub of community knowledge. It links to key documents such as: [Go Code Review Comments](https://go.dev/wiki/CodeReviewComments), [Go Test Comments](https://go.dev/wiki/TestComments), [Go Style Decisions](https://google.github.io/styleguide/go/decisions) and many others.

---

### 2.2. Tools

Go is famous for its philosophy that “the toolchain is part of the language.” In other words, most of what you need comes built-in: formatting (gofmt), testing, building, and even documentation tools.

However, one essential addition for any serious project is [golangci-lint](https://golangci-lint.run/). It combines multiple linters into one fast, easy-to-use tool. From day one, it helps you write clean, idiomatic, and bug-free code by catching issues early — before they reach production.

Highly recommended for both solo projects and team workflows.

---

## 3. Advanced Topics

### 3.1. Mastering Go

Choose your learning method — tour, code, course, or community — and start building.

A great way to deepen your knowledge is to recreate familiar technologies from scratch.  
If you're looking for inspiration, the ["Build Your Own X"](https://github.com/codecrafters-io/build-your-own-x) list is an amazing resource.

One of my favorite challenges is building a Redis-like database. While plenty of them exist, I’ve created my own version:
[Simple Key-Value Store](https://github.com/dzyanis/minikv/blob/main/README.md)

---

### 3.2. Trainings

[Ardan Labs – Ultimate Go](https://www.ardanlabs.com/training/ultimate-go/) is advanced-level training by Go veterans. Not suitable for beginners, but excellent for serious developers.

---

## Acknowledgments

- [Dan Horbatt](https://www.linkedin.com/in/danhorbatt/)
- [Oleg Balunenko](https://www.linkedin.com/in/olegbalunenko/)
- [Ruslan Panamarenka](https://www.linkedin.com/in/sevenwhite/)


## P.S.

If you have any suggestions or ideas to improve this article — I’d love your feedback! 🙏