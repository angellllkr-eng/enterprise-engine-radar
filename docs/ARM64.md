# ARM64-first multi-architecture notes

Goal: prefer ARM64 (Apple Silicon, AWS Graviton, Oracle Ampere) while still shipping amd64.

## Local (Apple Silicon)
```bash
docker buildx create --use --name mindreply-builder
docker buildx build --platform linux/arm64 -t mindreply/radar:local -f docker/Dockerfile.multiarch .
```

## Push multi-arch
```bash
docker buildx build --platform linux/arm64,linux/amd64 \
  -t ghcr.io/angellllkr-eng/llm-gateway:latest \
  -f docker/Dockerfile.multiarch --push .
```

## Why
- Lower cost on cloud ARM
- Native speed on your Mac
- One Dockerfile, two architectures

No paid Docker Build Cloud required for basic multi-arch. Use it only if you outgrow free buildx minutes.
