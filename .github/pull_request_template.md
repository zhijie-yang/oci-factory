- [ ] I have signed the [CLA](http://www.ubuntu.com/legal/contributors/)?
- [ ] I am following the [CONTRIBUTING](https://github.com/canonical/oci-factory/blob/main/CONTRIBUTING.md) guidelines

---

## Description
<!--- Describe your changes in detail -->

### Related issues
<!--- If related to an issue, reference it -->
<!--- Link the issue using GitHub's keywords -->
<!--- https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword -->

---

- type: dropdown
  attributes:
    label: Type
    description: What type best describes this work item?
    multiple: false
    options:
      - Onboard of a new image
      - Image trigger update
      - Image documentation update
      - Image misc update
      - Other
  validations:
    required: false  <!--- Run an agentic workflow to determine the rock/<type> if not chosen --->

- type: dropdown
  attributes:
    label: Urgency
    description: What is the due date of this work item?
    multiple: false
    options:
      - No hard limits
      - Within a week
      - Within a pulse (2 weeks)
      - Within a month
      - Within a cycle
    default: 0
  validations:
    required: true

---

*Picture of a cool rock:*
