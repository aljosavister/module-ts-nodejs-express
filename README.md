# Express module

This module contains Express web framework template for Node.js TypeScript project.

It contains:
- REST API POST request route: http://localhost:3200/api/call
- REST API POST upload route: http://localhost:3200/api/upload
- Default public folder that resolves to http://localhost:3200/
- API class with predefined options for session cookies, appContext

Module can be added to the project with ntscli:
```
cd myproject
npx ntscli express .
```
## Disclaimer: Not for Production use

This code is provided for educational purposes and should **not** be used in production environments. It has not undergone the necessary testing, security checks, and optimizations required for reliable and secure production use. Deploying it in such contexts may lead to unforeseen issues and vulnerabilities. Use it at your own risk, and exercise caution when considering production deployment.
