from node:22-alpine

workdir /app

copy . .

run bun install
run bun run build

expose 3000

cmd ["bun", "run", "dev"]