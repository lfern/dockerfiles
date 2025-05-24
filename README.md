# 🐳 Dockerfiles Collection

This repository contains a curated collection of Dockerfiles maintained by me, covering various tools, runtimes, frameworks, and development environments.

Whether you're working with blockchain stacks like Polkadot SDK or Cosmos SDK, setting up developer tools, or building base images for CI/CD workflows, this repo aims to provide reusable and well-documented Docker images for multiple use cases.

---

## 📦 Included Images

Some of the Dockerfiles you’ll find here include:

- **Blockchain Development**
  - Custom images based on `paritytech/ci-unified` with Substrate tooling
  - Cosmos SDK build and test environments
- **DevOps & CI/CD**
  - Lightweight CI containers for Rust, Node.js, Python, etc.
  - Images with pre-installed testing and automation tools
- **Tooling & Utilities**
  - CLI environments
  - System-level debugging tools
  - Script runners and pre-baked shells

Each directory contains its own `Dockerfile` and documentation.

---

## 📤 Where to Find the Published Images

Most images are published to [my Docker Hub account](https://hub.docker.com/u/lfern70).

Each image has its own documentation and tags listed in its corresponding directory or Docker Hub page.

---

## 🤝 Contributing / Feedback

This is a personal/experimental collection, but feedback and improvements are welcome.

If you'd like to request a feature or report a problem with a specific image, open an issue or discussion.

---

## 🕰️ Legacy or Archived Images

Older Dockerfiles or experimental setups are placed in the `legacy/` folder. These are not actively maintained but may still serve as useful references.

---

## 🔗 See Also

- [Docker Official Images](https://hub.docker.com/search?q=&type=image&image_filter=official)
- [Polkadot SDK](https://github.com/paritytech/polkadot-sdk)
- [Cosmos SDK](https://github.com/cosmos/cosmos-sdk)
