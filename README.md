# uselocation-bug-repl

Steps done:
1. npm init @vitejs/app (choose svelte > javascript)
2. cd vite-project && npm install
3. npm install svelte-navigator --save
4. added error showcase

To reproduce:
1. cd vite-project && npm ci && npm run dev
2. go to localhost:3000
3. click error page and see console

---

When u run npm build and try /dist/index.html, then here it works. Vite build uses rollup. 