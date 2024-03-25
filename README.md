## 9ssi7 Lab

This repository serves as a playground for experimentation and development of various tools and libraries in Go. It leverages Git's submodules functionality to centrally manage smaller, focused projects within a single codebase. 

The key benefits of this approach include:

* **Improved Code Organization:** By utilizing submodules, the codebase remains organized and modular, with each project having its own dedicated directory.
* **Version Control and Collaboration:** Each submodule can be independently version-controlled, allowing for easier tracking of changes and collaboration on specific projects.
* **Reusable Components:** Well-tested and maintained submodules can be easily integrated into other projects, promoting code reuse and reducing development time.

### Available Submodules

Here's a brief overview of the currently available submodules in this repository, along with links to their respective READMEs:

* [**KPSPublic**](./KPSPublic/) - Go client library for interacting with the Turkish Tax Administration's KPSPublic SOAP service.
* [**acc**](./acc/) - Accumulator: a Go library designed to manage and process data accumulations efficiently.
* [**cillop**](./cillop/) - Cillop is a scalable and modular application architecture for building robust and maintainable Go applications.
* [**dockerfile**](./dockerfile/) - This core submodule provides Dockerfiles for various programming languages and frameworks, promoting performance and streamlined deployments.
* [**nanoid**](./nanoid/) - Lightweight Go package for generating short, unique IDs as an alternative to lengthy UUIDs.
* [**slug**](./slug/) - Simple, fast, and lightweight slug generator library for Go projects.
* [**tguard**](./tguard/) (time guard) - Manages data with specific timeouts in Go applications, including functionalities for starting, canceling, and managing data based on their TTL (time-to-live) settings.
* [**turnstile**](./turnstile/) - Go client library for interacting with Cloudflare's Turnstile service (currently in private beta) used for protecting web applications from abuse.
* [**vkn**](./vkn/) - Go library for querying registered individuals or businesses in the Revenue Administration of Turkey.
* [**mono**](./mono/) - A monorepo boilerplate for building and deploying microservices-based applications using Docker.
* [**papara**](./papara/) - A golang rest client for papara API.

This repository welcomes contributions! Feel free to open issues, suggest improvements, or submit pull requests to enhance these tools and libraries.
