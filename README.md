# Kerem Kazan

Systems engineer in New York City focused on ML infrastructure, low-latency
C++, deep learning systems, and distributed infrastructure.

I have spent nine years building startup systems across language-model
evaluation, real-time networks, cloud infrastructure, developer tooling, and
product platforms. My current work is centered on understanding and building
the machinery behind modern deep learning systems.

## Current projects

### Deep Learning, All the Way Down

A code-first video series that rebuilds deep learning from first principles in
modern C++.

The implementation currently includes tensor storage and indexing, reductions,
elementwise operations, matrix multiplication, broadcasting, mean squared
error, computation graphs, and scalar reverse-mode automatic differentiation.
The project will continue toward tensor autograd, training loops, neural
networks, transformers, performance engineering, GPU programming, and custom
CUDA kernels.

[Source code](https://github.com/mechanical-turk/deep-learning-all-the-way-down)
· [YouTube series](https://www.youtube.com/playlist?list=PLZSg76FHvdTw)

### Chess Commentator Transformer

An encoder-decoder transformer trained to generate tactical commentary for
chess moves. The project covers data mining, quality analysis, custom
tokenization, model training, and post-training evaluation with PyTorch and
Hugging Face.

[Source and notebooks](https://github.com/mechanical-turk/chess-commentator-transformer)
· [Video walkthrough](https://www.youtube.com/watch?v=TRrfl2bLbKY)

## Selected systems work

### Language-model evaluation infrastructure

At Haize Labs, I built the core test harness used for red-team and functional
testing across hundreds of thousands of daily language-model conversations,
their evaluations, and their taxonomies. I also led a directed-graph interface
for maintaining large suites of functional model tests.

### High-performance RPC gateway

I authored a caching RPC load balancer in Rust and integrated it into production
infrastructure. It served roughly 1,000 to 2,000 requests per second on 0.5 vCPU
and 250 MB of memory, cut upstream API costs by about 50%, and saved more than
$20,000 per month.

The gateway supports HTTP and WebSocket traffic, caching, health monitoring,
load balancing, Docker, Kubernetes, and configurable observability.

[Source code](https://github.com/whats-good/rpc-gateway)

### Distributed messaging infrastructure

At Here Not There, I led cloud infrastructure for a decentralized, real-time,
end-to-end encrypted messaging network. The work included Kubernetes,
observability for externally operated nodes, reproducible sandbox environments,
protocol infrastructure, and a migration from AWS ECS to GCP Kubernetes.

### Startup systems and developer platforms

I joined Matter as its first employee and led architecture across databases,
caching, queues, serverless workloads, GraphQL APIs, testing, CI, and frontend
infrastructure. I also built recommendation systems and an internal A/B testing
platform.

Earlier open-source work includes
[Uniform GraphQL](https://github.com/whats-good/uniform-graphql), a code-first
type-safe GraphQL framework, and
[VulcanJS CLI](https://github.com/VulcanJS/vulcanjs-cli), a community-adopted
scaffolding tool distributed through npm.

## Technical focus

- **Languages:** C++, Rust, Python, TypeScript
- **Machine learning:** PyTorch, transformers, model evaluation, data pipelines,
  automatic differentiation
- **Systems:** distributed systems, caching, load balancing, observability,
  profiling, resource efficiency
- **Infrastructure:** Kubernetes, Terraform, Docker, AWS, GCP, Cloudflare,
  Datadog
- **Currently studying:** numerical computing, deep learning internals, CUDA,
  and custom GPU kernels

## Background

- BSE in Computer Science, University of Pennsylvania
- Former founding engineer, engineering leader, and startup co-founder
- 0xMacro Secure Smart Contract Engineering Fellowship, honors tier
- Product Hunt Golden Kitty Award for Social Impact with Matter
- Co-inventor on a pending patent for automated performance feedback

## Connect

- [YouTube](https://www.youtube.com/@mechaturka)
- [LinkedIn](https://www.linkedin.com/in/keremkazan)
- [X](https://x.com/mechaturka)
- [Email](mailto:kerem.kazan@gmail.com)
