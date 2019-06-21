# learning-javascript-01

テクノロジー（藤原）JavaScriptの練習 (1)

## Q1の回答「コメントを解除したことで、どう変化しましたか？」

ページを更新した際、ポップアップでこんにちは！とでてきた
## Q2の回答「エラーの原因は何でしょうか？（調べてみましょう）」

ウインドウが定義されていない


## Chromeデベロッパーツール：Consoleの実行結果

```
index.html:18 おはよう！
Navigated to http://127.0.0.1:5500/index.html
index.html:18 おはよう！
Navigated to http://127.0.0.1:5500/index.html
index.html:18 おはよう！
favicon.ico:1 GET http://127.0.0.1:5500/favicon.ico 404 (Not Found)
Navigated to http://127.0.0.1:5500/index.html
VM223 main.js:4 Good morning.
index.html:18 おはよう！
Navigated to http://127.0.0.1:5500/index.html
VM246 main.js:4 Good morning.
index.html:18 おはよう！
favicon.ico:1 GET http://127.0.0.1:5500/favicon.ico 404 (Not Found)
Navigated to http://127.0.0.1:5500/index.html
VM274 main.js:4 Good morning.
index.html:18 おはよう！
Navigated to http://127.0.0.1:5500/index.html
VM297 main.js:4 Good morning.
index.html:18 おはよう！
favicon.ico:1 GET http://127.0.0.1:5500/favicon.ico 404 (Not Found)
Navigated to http://127.0.0.1:5500/index.html
VM325 main.js:4 Good morning.
index.html:18 おはよう！
Navigated to http://127.0.0.1:5500/index.html
main.js:4 Good morning.
index.html:18 おはよう！
favicon.ico:1 GET http://127.0.0.1:5500/favicon.ico 404 (Not Found)
Navigated to http://127.0.0.1:5500/index.html
main.js:4 Good morning.
index.html:18 おはよう！
favicon.ico:1 GET http://127.0.0.1:5500/favicon.ico 404 (Not Found)
```

## ターミナルの実行結果

```takuto@DESKTOP-8UMKL44:~$ cd fujiwara
takuto@DESKTOP-8UMKL44:~/fujiwara$ git clone git@github.com:mizusimatakuto/learning-javascript-01.git
Cloning into 'learning-javascript-01'...
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (8/8), done.
remote: Total 10 (delta 0), reused 7 (delta 0), pack-reused 0
Receiving objects: 100% (10/10), done.
takuto@DESKTOP-8UMKL44:~/fujiwara$ cd learning-javascript-01
takuto@DESKTOP-8UMKL44:~/fujiwara/learning-javascript-01$ code .
takuto@DESKTOP-8UMKL44:~/fujiwara/learning-javascript-01$ node node-main.js
/mnt/c/Users/mizut/Documents/fujiwara/learning-javascript-01/node-main.js:1
window.alert("Hello, Node.js!!");
^

ReferenceError: window is not defined
    at Object.<anonymous> (/mnt/c/Users/mizut/Documents/fujiwara/learning-javascript-01/node-main.js:1:1)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
takuto@DESKTOP-8UMKL44:~/fujiwara/learning-javascript-01$ node node-main.js
/mnt/c/Users/mizut/Documents/fujiwara/learning-javascript-01/node-main.js:1
window.alert("Hello, Node.js!!");
^

ReferenceError: window is not defined
    at Object.<anonymous> (/mnt/c/Users/mizut/Documents/fujiwara/learning-javascript-01/node-main.js:1:1)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
takuto@DESKTOP-8UMKL44:~/fujiwara/learning-javascript-01$ node node-main.js
/mnt/c/Users/mizut/Documents/fujiwara/learning-javascript-01/node-main.js:1
window.alert("Hello, Node.js!!");
^

ReferenceError: window is not defined
    at Object.<anonymous> (/mnt/c/Users/mizut/Documents/fujiwara/learning-javascript-01/node-main.js:1:1)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
takuto@DESKTOP-8UMKL44:~/fujiwara/learning-javascript-01$ node node-main.js
takuto@DESKTOP-8UMKL44:~/fujiwara/learning-javascript-01$ node node-main.js
takuto@DESKTOP-8UMKL44:~/fujiwara/learning-javascript-01$






```

