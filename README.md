Install truffle and testrpc
start testrpc
truffle compile
truffle migrate


copy the abi key for test contract in truffle migrate console to following files in App-server\js:
main.js (VotingContract.at)
index_user.js
policy.js
claim.js

Launch index.html in browser

//
No longer needed.
//
truffle console, this will launch truffle(development)

run command json.stringify(test.abi)

copy the abi file generated in main.js

