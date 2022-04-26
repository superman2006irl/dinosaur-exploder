body:
- type: textarea
  attributes:
    label: Pull request
    description: Please concisely describe the changes you have made.
  validations:
    required: false
- type: textarea
  attributes:
    label: Issue Link
    description: Issue reference number and link goes here e.g. 'Fixes #5'.
  validations:
    required: false

- type: checkboxes
  attributes:
    label: 👉 Please make sure to check off the following before submitting
    options:
      - label: I have reviewed my submission thoroughly
        required: true 
      - label: I have tested my code (if submission is related to coding)
        required: true
      - label: I have read the [Code of Conduct](https://github.com/dylan-power/dinosaur-exploder/blob/main/CODE_OF_CONDUCT.md) and [contribution guidelines] (https://github.com/dylan-power/dinosaur-exploder/blob/main/CONTRIBUTING.md)
        required: true
