# API Stand Automated Tests

Automated API testing project developed during the TripleTen QA Engineering Bootcamp.

## Project Overview

This repository demonstrates the use of Python, pytest, and the Requests library to validate REST API behavior. The tests focus on user creation and input validation for the `firstName` parameter, including positive and negative scenarios derived from the application requirements.

## QA Skills Demonstrated

- REST API testing
- Positive and negative test design
- Equivalence partitioning
- Boundary value analysis
- HTTP response and status-code validation
- JSON request payload validation
- Reusable request functions
- Automated assertions with pytest
- Git and GitHub version control

## Technologies

- Python
- pytest
- Requests
- REST APIs
- JSON
- Git and GitHub
- PyCharm

## Project Structure

- `configuration.py` — server URL and API endpoints
- `data.py` — request headers and test data
- Python test modules — automated API scenarios
- `README.md` — project documentation

## Running the Tests

1. Clone the repository:

```bash
git clone https://github.com/SergioBeltran-QA/api_stand_tests.git
cd api_stand_tests
```

2. Create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
```

3. Install the dependencies:

```bash
python -m pip install pytest requests
```

4. Start a TripleTen test server and replace `URL_SERVICE` in `configuration.py` with the current server URL.

5. Execute the test suite:

```bash
python -m pytest -v
```

## Notes

The TripleTen server URLs are temporary and may no longer be active. A current test-environment URL is required to execute the suite.

All names, phone numbers, addresses, and other values included in the repository are test data and do not represent real customer information.

## Author

**Sergio Beltrán**  
Junior QA Engineer specializing in web, mobile, API, and database testing.

- [GitHub Profile](https://github.com/SergioBeltran-QA)
- [LinkedIn](https://www.linkedin.com/in/sergio-beltr%C3%A1n-/)
