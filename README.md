<div align="center">
  <br />
    <a href="" target="_blank">
      <img src="https://github.com/EDProgrammerist/sports-events_websockets/blob/master/public/readme/Thumbmail.jpg?raw=true" alt="Project Banner">
    </a>
  <br /> 

  <div>
<img src="https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white" /> 
<img src="https://img.shields.io/badge/-Express_5-000000?style=for-the-badge&logo=Express&logoColor=white" /> 
<img src="https://img.shields.io/badge/-WebSockets-010101?style=for-the-badge&logo=Socket.io&logoColor=white" />
  <img src="https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=React&logoColor=black" />
<br/>
<img src="https://img.shields.io/badge/-PostgreSQL-4169E1?style=for-the-badge&logo=PostgreSQL&logoColor=white" /> <img src="https://img.shields.io/badge/-Drizzle-C5F74F?style=for-the-badge&logo=Drizzle&logoColor=black" /> 
<img src="https://img.shields.io/badge/-Zod-3E67B1?style=for-the-badge&logo=Zod&logoColor=white" />
<br/>
<img src="https://img.shields.io/badge/-Arcjet-5C2D91?style=for-the-badge&logo=Arcjet&logoColor=white" /> 
<img src="https://img.shields.io/badge/-Site24x7-26CD66?style=for-the-badge&logo=Site24x7&logoColor=white" /> <img src="https://img.shields.io/badge/-CodeRabbit-000000?style=for-the-badge&logo=CodeRabbit&logoColor=white" /> 

  </div>

  <h3 align="center">Live Sports Events | Websockets Course</h3>

   <div align="center">
    <a href="" target="_blank"><b></b></a>
    </div>
</div>

## 📋 <a name="table">Table of Contents</a>

1. ✨ [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)

## 🚨 Tutorial
Thank you so much for the informative tutorial it significantly enhanced my understanding of WebSockets, <a href="https://www.youtube.com/watch?v=pbOXOY78dNA&t=306s" target="_blank"><b>JavaScript Mastery</b></a>.

## <a name="introduction">✨ Introduction</a>

Sportz is a comprehensive backend service designed for live sports coverage, utilizing REST endpoints for match and commentary management alongside WebSockets for real-time data broadcasting. The platform allows clients to monitor match lists and receive instantaneous score and play-by-play commentary updates through a robust streaming architecture that features heartbeats, rate limiting, and backpressure protection. By enforcing live-only updates and utilizing Zod schemas for strict input validation, Sportz ensures a reliable and structured flow of information; additionally, the service includes dedicated seeding tools to simulate live game environments and facilitate development.

## <a name="tech-stack">⚙️ Tech Stack</a>

- **[React](https://react.dev/)** is a declarative, component-based UI library that helps developers build interactive user interfaces with efficient rendering. It provides core primitives for state management, component lifecycle, and a virtual DOM, ensuring that applications remain performant, scalable, and easy to maintain across complex web environments.

- **[Arcjet](https://jsm.dev/sportz-arcjet)** is a security-first tool that helps developers protect their applications with just a few lines of code. It provides security primitives for rate limiting, bot protection, email validation, and sensitive data masking, ensuring the application remains secure and resilient.

- **[PostgreSQL](https://www.postgresql.org/)** is a powerful, open-source relational database system known for its reliability, data integrity, and robust feature set. It supports advanced data types, full ACID compliance, and extensibility, making it suitable for a wide range of applications.

- **[Drizzle ORM](https://orm.drizzle.team/docs/overview)** is a lightweight and performant TypeScript ORM designed with developer experience in mind. It provides a seamless interface between application code and database operations while maintaining high performance and reliability.

- **[Drizzle Kit](https://orm.drizzle.team/kit-docs/overview)** is a CLI companion for Drizzle ORM that automates database migrations and schema synchronization; it ensures that your database structure remains consistent with your TypeScript definitions through efficient code generation.

- **[Node.js](https://nodejs.org/)** is an open-source, cross-platform JavaScript runtime environment that executes JavaScript code outside a web browser. It is designed to build scalable network applications and serves as the foundation for the project's backend logic.

- **[Express.js](https://expressjs.com/)** is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications. It facilitates the rapid development of RESTful APIs and serves as the standard server framework for the Node.js ecosystem.

- **[CORS Middleware](https://github.com/expressjs/cors)** is a package for Express that provides a simple mechanism to enable Cross-Origin Resource Sharing; it manages the security headers required to allow or restrict web applications from making requests to a different domain.

- **[Dotenv](https://github.com/motdotla/dotenv)** is a zero-dependency module that loads environment variables from a .env file into process.env; it helps keep configuration separate from code and secures sensitive credentials like API keys and database strings.

- **[WebSockets](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API)** is a communication protocol that provides full-duplex communication channels over a single TCP connection; it enables real-time, bi-directional interaction between a client and a server without the overhead of traditional HTTP polling.

- **[WS Library](https://github.com/websockets/ws)** is a simple-to-use, blazing-fast, and thoroughly tested WebSocket client and server implementation for Node.js; it serves as a high-performance foundation for building scalable real-time applications.

- **[Zod](https://zod.dev/)** is a TypeScript-first schema declaration and validation library; it allows developers to define data structures and automatically infer types, ensuring that input data is strictly validated and type-safe at runtime.

### Dev Tools
- **[CodeRabbit](https://jsm.dev/sportz-coderabbit)** is an AI-powered code review platform that provides automated, contextual feedback on pull requests. It helps developers improve code quality and catch potential bugs early by integrating directly into the development workflow.

- **[Hostinger](https://jsm.dev/sportz-hostinger)** is a high-performance web hosting provider that offers scalable solutions for deploying web applications; it provides a user-friendly interface, optimized server performance, and robust security features to ensure reliable uptime and accessibility for your projects.

- **[Site24x7](https://jsm.dev/sportz-site24x7)** is a comprehensive monitoring solution that provides deep insights into application performance and infrastructure health. It allows for real-time tracking of uptime, end-user experience, and server metrics to ensure maximum availability.



## <a name="features">🔋 Features</a>

👉 **Match Management**: Effortlessly list and create sports matches while maintaining accurate updates for scores and match statuses.

👉 **Commentary Management**: Access comprehensive play-by-play commentary tied to specific matches and add new entries to keep the coverage current.

👉 **Real-Time Broadcasts**: Deliver instant commentary and score updates via per-match WebSocket subscriptions, ensuring clients receive live data as it happens.

👉 **WebSocket Protocol**: Utilize a structured messaging system for subscribing, unsubscribing, and managing active subscriptions with automated ping responses.

👉 **Robust WS Behavior**: Maintain high performance and stability through the use of heartbeats, backpressure protection, rate limiting, and subscription caps.

👉 **Input Validation**: Ensure data integrity across both REST endpoints and WebSocket messages using strict Zod schemas.

👉 **Seed Tooling**: Rapidly populate matches and simulate live commentary and score changes with a dedicated script designed for testing and simulation.

And many more, including code architecture and reusability.

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone [git remote URL]
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

