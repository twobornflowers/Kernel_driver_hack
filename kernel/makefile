name: name: Makefile CI:Makefile CI

on:
  push:
    branches: [    branches: [ "main" ]:[ "main" ]"主要""main"]
  pull_request:
    branches: [    branches: [ "main" ]:[ "main" ]"main" ]

jobs:
  build:

    runs-on:     runs-on: ubuntu-latest:Ubuntu-最新版

    steps:
    - uses:     - uses: actions/checkout@v4: actions/checkout@v4

    - name:     - name: configure:配置
      run:       run: ./configure:。/配置

    - name:     - name: Install dependencies:安装依赖项
      run:       run: make:制作

    - name:     - name: Run check:运行检查
      run:       run: make check:进行检查

    - name: Run distcheck
      run: make distcheck
