# setup

1. brew install chromium --no-quarantine
2. add following environment variable to .zshenv

```sh
export PUPPETEER_SKIP_CHROMIUM_DOWNLOAD=true
export PUPPETEER_EXECUTABLE_PATH=`which chromium`
```

# how to run

```sh
npx fusuma start
```