#### TAILWIND STARTER  

- INSTALL

1. NodeJS +
2. node -v (check version Nodejs)
3. npm -> Node package manager (install , uninstall)
4. node_modules -> Node packages
5. package.json
6. package-lock.json
7. npx -> node package executed (js file)



- ### TAILWIND STARTER installing proccess

1. tailwindCSS.com
2. get Started
3. `` npm install -D tailwindcss``
4. `` npx tailwindcss init --full ``
5. "/dist/style.css"
 
 ``  @tailwind base;
     @tailwind components;
     @tailwind utilities
 ``
6. index.html -> CDN  inner head tag in html file
```
<script src="https://cdn.tailwindcss.com"></script>

```

7. watch style.css

```
npx tailwindcss -i ./dist/style.css -o ./dist/output.css --watch

```

8. Tailwind CSS IntelliSense (vs code exstension)