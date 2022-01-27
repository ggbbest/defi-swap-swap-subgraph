# Defi Swap - Swap subgraph

Uniswap Fork, subgraph for https://crypto.com/defi/swap

## Mainnet Canary Subgraph

Deployment happens on pull request

https://thegraph.com/explorer/subgraph/crypto-yang/defi-swap-subgraph

## Mainnet Production Subgraph

Deployment happens on merge to master branch

https://thegraph.com/explorer/subgraph/c4ei-net/swap-subgraph

https://thegraph.com/hosted-service/subgraph/ggbbest/swap
npm install -g @graphprotocol/graph-cli
yarn global add @graphprotocol/graph-cli

graph auth --product hosted-service #########apikey#########
graph deploy --product hosted-service ggbbest/swap



/home/dev/www/farm_swap/swap-subgraphs/package.json
yarn codegen

<!-- graph deploy --product hosted-service ggbbest/swap --ipfs https://api.thegraph.com/ipfs/ --node https://api.thegraph.com/deploy/ --debug -->


22-01-27
yarn codegen
yarn create-local
yarn deploy-local
Build completed: QmYzGux6DDrML1cPyH4VB8jzesPEyQJhFJ3f98YRSFJBPn
Deployed to https://subgraph.c4ei.net/subgraphs/name/c4ei/swap/graphql
Subgraph endpoints:
Queries (HTTP):     https://subgraph.c4ei.net/subgraphs/name/c4ei/swap
Subscriptions (WS): http://127.0.0.1:8001/subgraphs/name/c4ei/swap

