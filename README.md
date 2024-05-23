# The Official Vite Dapp Template

# Getting Started
```
# git pull submodules
git submodule update --init --recursive

# install deps 
npm --prefix ./frontend install
npm --prefix ./vitasensus-operator-server install 

# build and run api
cd frontend
npm run build:api
npm run start

# run frontend
npm run debug

# run unit test for test/*.spec.ts
npx vuilder test

# deploy contract
# edit scripts/deploy.config.json && run deploy scripts
npx ts-node scripts/deploy.ts

# stake quota for contract(by web-wallet)

```