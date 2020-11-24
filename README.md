1. Setup. Install Protractor globally with:   
    npm install -g protractor
    webdriver-manager update
    webdriver-manager start
   
2. Update libraries:
    Settings/Languages/JavaScript/Libraries
    check HTML, protractor/node_modules, @types/node
    
3. update config file:
    compare with prot.conf.js and add everything that is missing

4. install devDependencies (they do not go to the production),
    go to Terminal and type:
    npm install -save--dev @types/protractor
    npm install -save--dev jasmine-spec-reporter
    
5. to run test: npm test