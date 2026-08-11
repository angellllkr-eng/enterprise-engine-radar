# Multi-arch friendly image for the radar static site + optional Node tools
FROM --platform=$BUILDPLATFORM node:22-alpine AS base
WORKDIR /app
COPY package*.json ./
RUN npm ci --omit=dev || true
COPY . .

# Final stage — works on amd64 and arm64
FROM node:22-alpine
WORKDIR /app
COPY --from=base /app .
EXPOSE 3000
CMD ["npx", "serve", "-s", "site", "-l", "3000"]
