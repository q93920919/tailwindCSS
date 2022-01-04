### 安装 Tailwind

```javascript
npm install -D tailwindcss
```

### 创建配置文件

```javascript
npx tailwindcss init
```

### 根目录下添加tailwind.config.js

```
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

### 新建引入tailwind的tailand.css

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### main.js中引入css

```
import './tailand.css'
```



### 报错 Error: Error: PostCSS plugin tailwindcss requires PostCSS 8.

```
npm uninstall tailwindcss postcss autoprefixer
npm install -D tailwindcss@npm:@tailwindcss/postcss7-compat postcss@^7 autoprefixer@^9
```