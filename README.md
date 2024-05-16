# Playwright-With-Nodejs
# **Installation :**

### **Using Command Line:**
npm init playwright@latest
### **Using GUI:**
- Go to vsCode.
- Open Extension Icon 
- Write **PlayWrite Microsoft** 
- Install 
### **Playwright Runner for Headless testing:**
- Go to vsCode.
- Open Extension Icon 
- Write **PlayWrite Test For VSCode**
- Install
- Then you see the icon on left side of the Vs code for test runner
- Just click on file/ Folder you want to run and click on run button 

# **Test Case Running Commands:**
- #### npx playwright test (runs all tests on all browsers in headless mode)
- #### npx playwright test --workers 3 (runs with 3 workers in parallel)
- #### npx playwright test test.spec.js (runs a specific test file)
- #### npx playwright test test1.spec.js test2.spec.js (runs the files specified)
- #### npx playwright test login signup (runs files that have login signup in the file name)
- #### npx playwright test -g "Login" (runs test with the title)
- #### npx playwright test --project=chromium (runs on specific browser)
- #### npx playwright test --headed (runs tests in headed mode)
- #### npx playwright test --debug (debug tests)
- #### npx playwright test test.spec.js --debug (debug specific test file)
- #### npx playwright test test.spec.js:21 --debug (debug starting from specific line)




