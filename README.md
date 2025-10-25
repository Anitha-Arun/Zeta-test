# E-Commerce Testing Assignment

Hey! This repo has all my testing work for the e-commerce application.

## What's Inside

- **web-automation**: Selenium tests for the website
- **api-testing**: Postman collection for API tests
- **performance-testing**: k6 script for load testing
- **screenshots**: Test execution results

## Quick Start

### Running Web Tests
```bash
cd web-automation
pip install -r requirements.txt
python test_checkout.py
```

### Running API Tests
Import the Postman collection from `api-testing` folder into Postman and hit run.

Or use Newman:
```bash
newman run api-testing/ecommerce_api_tests.postman_collection.json
```

### Running Load Tests
```bash
cd performance-testing
k6 run load_test_checkout.js
```

## Tools Used

- **Web Automation**: Python + Selenium
- **API Testing**: Postman
- **Test Site**: SauceDemo (https://www.saucedemo.com)

## Test Coverage

- Login and authentication
- Product browsing and search
- Shopping cart functionality
- Checkout process
- API endpoints
- Performance under load

## Notes

- All passwords and sensitive data are in environment variables
- Test data is in separate JSON files
- Screenshots saved automatically on test failure

## Contact

For questions, reach out to me at [anithadamarla0313@gmail.com]
