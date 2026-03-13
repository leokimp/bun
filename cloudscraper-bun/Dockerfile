FROM oven/bun:latest
WORKDIR /app
COPY package.json .
RUN bun install
COPY cloudscraper-bun.js .
EXPOSE 8000
CMD ["bun", "run", "cloudscraper-bun.js"]
