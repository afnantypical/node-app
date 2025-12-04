name: Node.js CI

on:
  push:
    branches: [ "main" ]
  pull_request:
    branches: [ "main" ]

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - name: Check out code
        uses: actions/checkout@v3

      - name: Set up Node.js
        uses: actions/setup-node@v4
        with:
          node-version: 18

      - name: Install dependencies
        run: npm install

      - name: Run tests (optional)
        run: echo "No tests defined"

      - name: Build (optional)
        run: echo "No build step"

      - name: Start app (demo)
        run: |
          echo "App would start with: npm start"
