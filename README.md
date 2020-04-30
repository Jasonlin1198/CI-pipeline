# CI-pipeline

Tests and lints using Jest tests and google's styling through ESLint on simple JS summation function

Runs pipeline on any pushes to repo

Steps to building:

1. addition.js holds summation function
2. addition.test.js holds Jest test: install jest using '''npm install --save-dev jest'''
3. Create github action workflow with lint.yml, format used from: 
      https://github.com/marketplace/actions/run-eslint 
      https://github.com/marketplace/actions/run-jest
4. Update package.json with
   ''' "scripts": {
        "test": "jest"
     },'''
5. git add, git commit, git push 
6. Check pass/fail in Actions tab in github


Install ESLint locally:
https://eslint.org/docs/user-guide/getting-started

1. '''npm install eslint --save-dev'''
2. '''npx eslint --init'''
3. '''npx eslint yourfile.js'''
