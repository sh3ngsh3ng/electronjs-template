# Template is done with reference to:
- https://www.electronjs.org/docs/latest/tutorial/quick-start



# Packaging Electron Application
- Step 1: Install electron-forge cli (--save-dev is to save as dev dependency)
```
npm install --save-dev @electron-forge/cli
```
- Step 2: npx executes package. <b>import</b> command sets up Forge's scaffolding
```
npx electron-forge import
```
- Step 3: Create a distributable using Forge's <b>make</b> command
```
npm run make
```


# Extra Information:
- Difference between npm and npx: https://www.geeksforgeeks.org/what-are-the-differences-between-npm-and-npx/#:~:text=Npm%20is%20a%20tool%20that,pollution%20in%20the%20long%20term.
