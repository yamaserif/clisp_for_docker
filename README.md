# clisp_for_docker
https://hub.docker.com/r/clfoundation/clisp

clispの実行環境です。\
（docker環境が必要です。）\
以下コマンドで実行可能です。

対話型(REPL)
```
docker compose run --rm lisp clisp
```

ファイルから実行
```
docker compose run --rm lisp clisp ./src/example/hello_world.lisp
```
