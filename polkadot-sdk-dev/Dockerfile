FROM paritytech/ci-unified:latest

RUN apt-get update && \
    apt-get install -y --no-install-recommends openssh-client && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*

RUN cargo install --locked staging-chain-spec-builder
RUN cargo install --locked polkadot-omni-node
RUN cargo install frame-omni-bencher

