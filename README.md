# PAIR WEB 
<ap href="https://asitha.top/pair"><img src="https://img.shields.io/badge/QR%20OR%20PAIR%20CODE-blue" alt="GET SESSION" width="200"></a>



## WORKFLOUR DEPLOY COD 🚀➤
```
name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install

    - name: Start application
      run: npm start
```
