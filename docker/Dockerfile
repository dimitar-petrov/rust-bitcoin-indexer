FROM rust:1.56.1 as builder
ENV USER root
COPY . /app
WORKDIR /app
RUN cargo build --release

CMD ["/app/target/release/bitcoin-indexer"]