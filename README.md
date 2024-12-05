This repo is used for an integration test to ensure `datadog-static-analyzer` correctly outputs "test file" classifications via SARIF.

# Development
* All `.js` files must contain exactly one violation.
* If a file's name starts with "should_be_t_file", the integration test will expect the analyzer to classify it as a "test file".
