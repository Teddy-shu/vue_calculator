# calculator

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
"# vue_calculator" 


### self note
```
簡單的vue 練習
用到了一個偷懶的方法 : 
在 data中 設定 operator 為一個function(initial NULL)
當操作者click operator 的 button 
operator function 會被設定為那個 operator button 的行為
例如 點擊 "+" button operator 會被指定為執行加法的行為
當 點擊 "=" 計算結果時 會執行 加法 把 兩數相加
```
