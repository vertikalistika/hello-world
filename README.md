# hello-world
1 GitHub
on: [push]

jobs:
  Hello:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout
        uses: actions/checkout@v2

      - name: Hello
        run: echo "Hello, GitHub Actions!"
