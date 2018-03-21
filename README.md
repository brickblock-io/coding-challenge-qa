# Brickblock Coding Challenge - QA

## The Goal
Your task is to write some end-to-end tests with [Cypress](https://www.cypress.io) to demonstrate your test automation abilities.

## What you'll need

1. The [Cypress Docs](https://docs.cypress.io)
1. The staging URL of our platform: [staging-platform.brickblock-cloud.io](https://staging-platform.brickblock-cloud.io)

## The Process

1. Fork this GitHub repo
1. In your forked repo, set up a new Cypress environment
1. Write some end-to-end tests fulfilling the [Acceptance Criteria](#acceptance-criteria) below
1. Create a pull request from your fork into this original repository.
1. In your pull request description, please document how to run the code you've written and how to verify the fulfilment of the acceptance criteria. Feel free to add additional thoughts, e.g. why you implemented a feature in a certain way, what were your learnings etc.
1. Mention @chapati23 or @mattgstevens in the pull request description to let us know you're ready for review. Alternatively, send us an email to dev@brickblock.io

## Acceptance Criteria
1. Write a first end-to-end test that
    1. Starts on the [landing page](https://staging-platform.brickblock-cloud.io)
    1. Clicks the CTA button leading to our [Know-your-Customer (KYC) form](https://staging-platform.brickblock-cloud.io/kyc)
    1. Verifies that all important information is there, e.g. existence of inputs, labels, checkboxes etc. (leaving this purposefully open to see what you think makes sense to test)
1. Write a second end-to-end test that
    1. Starts on the [KYC form](https://staging-platform.brickblock-cloud.io/kyc)
    1. Enters some invalid values into the form and leaves some fields empty
    1. Submits the form
    1. Verifies that you can't submit the form with invalid or missing values
    1. Verifies that error messages are shown
1. Write a last end-to-end test that
    1. Starts on the [KYC form](https://staging-platform.brickblock-cloud.io/kyc)
    1. Enters valid values into all form fields
    1. Submits the form
    1. Verifies that submitting the form with valid values results in a success message

## Bonus Round (not required, but nice-to-have)
* Usage of code quality tools such as eslint, prettier, flow or typescript
* Integration of your tests into a CI pipeline
* Screenshot diffing
* Surprise us…

## How we're evaluating the result
Prioritised from most important to least important, here are our evaluation criteria:

1. **Acceptance Criteria**: Have all acceptance criteria been fulfilled correctly?
1. **Code Quality**: Is the code that you've written clean, well-structured and easy to understand?
1. **Documentation**: Did you document how to run your tests well? Is your written communication clear and easy-to-understand?
1. **The extra mile**: Everything you did on top of the acceptance criteria. See [Bonus Round](#bonus-round)