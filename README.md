# Dependency API Demo
This is a toy app that utilizes the Dependency submission API. 

[About dependency submission API](https://docs.github.com/en/code-security/supply-chain-security/understanding-your-software-supply-chain/using-the-dependency-submission-api)

[Dependency submission API endpoint docs](https://docs.github.com/en/rest/dependency-graph/dependency-submission)

## Using this repo
Take a look at the [Dependency graph](https://github.com/octodemo/dependencies-demo-leftrightleft/network/dependencies).  You'll notice a snapshot section which identifies dependencies in `package.json`.  Those dependencies were submitted via the API.  You'll notice that `package.json` and `package-lock.json` actually don't contain any dependencies.

The file [api_call](https://github.com/octodemo/dependencies-demo-leftrightleft/blob/main/api_call) contains the `curl` command you'll need to updated the dependency graph.  Feel free to modify the body to play with it.  Be sure to include a new PAT with `repo` scope. 👍
 
  
 
  
asdf 
   s
bdfg
