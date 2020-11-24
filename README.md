1. Update libraries:
    Settings/Languages/JavaScript/Libraries
    check HTML, protractor/node_modules, @types/node
    
2. update config file:
    compare with prot.conf.js and add everything that is missing

3. install devDependencies (they do not go to the production),
    go to Terminal and type:
    npm install -save--dev @types/protractor
    npm install -save--dev jasmine-spec-reporter