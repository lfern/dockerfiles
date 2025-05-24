# 🧱 Polkadot SDK Dev Image with Omni Node & Chain Spec Builder
[![Docker Pulls](https://img.shields.io/docker/pulls/lfern70/polkadot-sdk-dev)](https://hub.docker.com/r/lfern70/polkadot-sdk-dev/tags) [![Docker Stars](https://img.shields.io/docker/stars/lfern70/polkadot-sdk-dev)](https://hub.docker.com/r/lfern70/polkadot-sdk-dev/tags) [![Docker Image Size](https://img.shields.io/docker/image-size/lfern70/polkadot-sdk-dev/latest)](https://hub.docker.com/r/lfern70/polkadot-sdk-dev/tags)



This Docker image extends [`paritytech/ci-unified`](https://hub.docker.com/r/paritytech/ci-unified) to include two essential tools for Substrate/Polkadot parachain development:

- 🛠️ **[staging-chain-spec-builder](https://crates.io/crates/staging-chain-spec-builder)**  
  Utility to generate chain specification (`chain_spec.json`) files for parachains.

- ⚙️ **[polkadot-omni-node](https://crates.io/crates/polkadot-omni-node)**  
  A generic parachain node binary that runs any parachain using a provided WASM runtime and chain spec — no need to compile a custom node binary.

---

## 🚀 What's Included

Built on top of `paritytech/ci-unified`, which includes:

- Rust toolchains
- Cargo and Substrate dependencies
- Common tools used in Polkadot SDK projects

Additional tools pre-installed:

- `staging-chain-spec-builder`
- `polkadot-omni-node`

---

## 🧪 Use Cases

- Quickly generate chain specs and boot up parachain nodes
- Run local development parachains without compiling your own node
- Integrate with CI/CD pipelines for parachain testing
- Ideal for tutorials, workshops, and prototyping

---

## 🏁 Getting Started

### Pull the image

```bash
docker pull lfern70/polkadot-sdk-dev:latest
```

### Run it interactively
```bash
docker run -it lfern70/polkadot-sdk-dev:latest bash
```

### Inside the container, try:

```bash
staging-chain-spec-builder --help
polkadot-omni-node --help
```

📦 **Available on Docker Hub**:  
👉 [docker.io/lfern70/polkadot-sdk-dev](https://hub.docker.com/r/lfern70/polkadot-sdk-dev)