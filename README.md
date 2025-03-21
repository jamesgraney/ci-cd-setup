# ci-cd-setup

## Description

To enhance the professionalism of development, I've implemented a CI/CD pipeline. Continuous Integration and Continuous Deployment ensure that new software updates are regularly delivered to customers. However, this requires developers to maintain high code quality and avoid frequent mistakes or, worse, breaking production.

This approach introduces multiple safeguards to uphold code quality while leveraging the advantages of automated testing.

If all tests pass, the update is deployed to the designated development platform—in this case, Render.

## Installation

Run npm i

## Usage
The GitHub Actions are configured to run component tests whenever the develop branch is triggered. Similarly, tests also run on the main branch as an additional verification step, though this may not be strictly necessary. For a production application, incorporating end-to-end tests at this stage could be beneficial. If the tests pass again, the code is then deployed to Render.


## Credits
N/A

## License
N/A