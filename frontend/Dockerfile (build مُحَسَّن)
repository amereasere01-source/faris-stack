FROM node:20-alpine
WORKDIR /app
COPY package.json pnpm-lock.yaml ./
RUN npm i -g pnpm && pnpm i --frozen-lockfile
COPY . .
RUN pnpm build
# الناتج يُرفع مجلد dist إلى nginx
