# Notes
-----

## Communicating an Idea
* Living Documentation
* Scenarios are Concrete Examples

## Example
### Requirement: 
A customer should be prevented from entering invalid credit card details.
### Concrete Example:
If a customer enters a credit card number that isn’t exactly 16 digits long, when they try to submit the form, it should be redisplayed with an error message advising them of the correct number of digits.
* Illustrates our requirements, think through the behavior

## Build trust in our code
* Slow Iterative Process

## Scenario
1. Get system into a particular state (context)
2. Do something (action)
3. Examine the new state (outcome)

Scenario: Successful withdrawal from an account in credit
  Given I have $100 in my account # the context
  When I request $20              # the event(s)
  Then $20 should be dispensed    # the outcome(s)

### Stateless
Each scenario must make sense and be able to be executed independently of any other scenario.

## Data Tables


## DAMP
Descriptive and Meaningful Phrases
* alternative to DRY
* In Gherkin DAMP trumps DRY

## Importance of ubiquitous language

# Cucumber's Big Secret
The tests and documentation are just a happy side effect; the real value lies in the knowledge you discover during those conversations.
