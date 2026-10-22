README.md
bun.lock
dist
docs
node_modules
package.json
src
tsconfig.json
tsr.config.json
vite.config.ts
whop.app.json
wrangler.jsonc
{
  "name": "django-launch-kit",
  "private": true,
  "type": "module",
  "imports": {
    "#/*": "./src/*"
  },
  "scripts": {
    "dev": "vite dev --port 3000",
    "generate-routes": "tsr generate",
    "build": "vite build",
    "preview": "vite preview",
    "deploy": "whop apps deploy",
    "typecheck": "tsc --noEmit"
  },
  "dependencies": {
    "@tailwindcss/vite": "^4.1.18",
    "@tanstack/react-devtools": "latest",
    "@tanstack/react-router": "latest",
    "@tanstack/react-router-devtools": "latest",
    "@tanstack/react-start": "latest",
    "react": "^19.2.0",
    "react-dom": "^19.2.0",
    "tailwindcss": "^4.1.18"
  },
  "devDependencies": {
    "@cloudflare/vite-plugin": "^1.26.0",
    "@tanstack/devtools-vite": "0.8.5",
    "@tanstack/router-cli": "^1.132.0",
    "@types/node": "^22.10.2",
    "@types/react": "^19.2.0",
    "@types/react-dom": "^19.2.0",
    "@vitejs/plugin-react": "^6.0.1",
    "typescript": "^6.0.2",
    "vite": "^8.0.0",
    "wrangler": "^4.70.0",
    "@whop/cli": "latest"
  },
  "pnpm": {
    "onlyBuiltDependencies": [
./src/router.tsx
./src/routes/index.tsx
./src/routes/__root.tsx
