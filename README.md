
# CI/CD Lab

A simple Node.js and Express application with automated CI checks using GitHub Actions.

## Commands

- `yarn start` - Start the application
- `yarn lint` - Check code quality
- `yarn test` - Run automated tests
- `yarn coverage` - Generate code coverage

To generate and open the HTML coverage report in PowerShell:

```powershell
corepack yarn coverage
Start-Process .\coverage\index.html
```
