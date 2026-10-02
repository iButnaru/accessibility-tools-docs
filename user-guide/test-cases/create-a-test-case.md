---
description: Step-by-step instructions on how to create a test case.
---

# 📁 Create a test case

**Accessibility Tools** comes with its own predefined set of test cases. However, we at Clym understand that your business needs may be unique, so we provide you with the capability to create and customize your own tests that better suit your individual needs.

To create your own test cases:

1. On the left-hand side navigation pane, click ![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfN6K0nU016Q_ZmoQWOd2opQSvaB2hhcBsnuNrefbMsvyulwRNZQmDv2P7xAAgJfu28gD-8Yh8jYlXFxjW3g95RQQ_-QDWcVV5exbQ6roh_bJH75Lg0eC-L2aUoDI09cJbMZGNy?key=_EQKB1eDe9ecbVZeBDg4Tw) **Test cases** and then click the **Add test case** button.
2. In the **Add test case** wizard screen, complete the fields:

<figure><img src="../../.gitbook/assets/image (71).png" alt=""><figcaption></figcaption></figure>

* **Test name** (mandatory): Give your new test a meaningful name.
* **Steps to reproduce**: Specify the steps to reproduce the test case.
* **Expected result**: Specify the desired outcome to successfully pass the test.
* **Additional instructions**: Enter any details to make the test easier to run.

Under **Technique:**

* **Category**: Select the desired technique category from the list.
* **Technique**: Select the desired technique from the list.

<figure><img src="../../.gitbook/assets/image (68).png" alt=""><figcaption></figcaption></figure>

Under **Targets:**

* **Test target**: Select the desired test target from the list.
* **Target format**: Select the desired target format from the list.
* **+Add additional targets** (optional): Create your own test targets, if different from the default ones. After clicking it, you also need to define the **Test target** and **Target format**.\
  When finished, click **Create** (if you opted to create another test target) or **Continue**.

<figure><img src="../../.gitbook/assets/image (69).png" alt=""><figcaption></figcaption></figure>

* In the next wizard screen, define the details of your **test case**, as follows:\
  \
  **Standard**: For now, the available standard is WCAG.\
  **Standard version**: Select the desired WCAG version of your test from the list.\
  **Principle**: Select the desired principle  from the list, such as, Perceivable, Operable, Understandable or Robust.\
  **Guideline**: Select the desired guideline from the list.\
  **Criterion**: Select the desired criterion from the list.\
  **Test type**: The default test type at this stage is manual.\
  When finished, click **Create**.

<figure><img src="../../.gitbook/assets/image (70).png" alt=""><figcaption></figcaption></figure>

Your newly-created test is now visible in the **Test Cases** section.

### View individual test cases

After [creating a project](../projects/create-a-project.md) and [running a test](../tests/create-a-test.md), you can see the test results displayed on the center pane, under **TEST CASES**. Click an individual test case to display the test case details on the right-hand pane, as follows:&#x20;

* Under Test case details:
  * Click Understanding \<technique number> to open the corresponding WCAG criterion in your browser. This is useful to determine if the remediation aims to fix the proper WCAG criterion.
* Click Remediations (if the test case fails) to see the recommended fixes of the test case.

Click **Notes** to add notes about the test. This is a useful feature to better identify the test in the future, given that the test cases come in great numbers and increased complexity.
