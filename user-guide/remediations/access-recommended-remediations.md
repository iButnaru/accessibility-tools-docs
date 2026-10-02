---
description: >-
  Some tests may have more than on remediation assigned to them, but one will
  always be recommended by default.
---

# ✔️ Access recommended remediations

When running a [test](../tests/create-a-test.md), you get a list of test cases and recommended remediations in the [test dashboard](../tests/view-and-act-on-test-results.md). Every test case that has a Failed or Inconclusive status will be provided with a recommended remediation.&#x20;

1. To see the recommended remediation, in the **Test results** screen, click the specific test at the bottom test cases list.

<figure><img src="../../.gitbook/assets/image (146).png" alt=""><figcaption></figcaption></figure>

2. On the right-hand side pane, the **test case details** is displayed next to the **Remediations** button.

<figure><img src="../../.gitbook/assets/image (147).png" alt=""><figcaption></figcaption></figure>

The recommended remediation for this particular test case is displayed, but you can click the ![](<../../.gitbook/assets/image (148).png>)**edit** button on the right-hand side of the remediation and choose a different one.

3. If needed, select another remediation from the respective list.&#x20;

<figure><img src="../../.gitbook/assets/image (149).png" alt=""><figcaption></figcaption></figure>

4. After selecting the desired remediation, click **Save**.

<figure><img src="../../.gitbook/assets/image (150).png" alt=""><figcaption></figcaption></figure>

5.  The selected remediation has been saved for the test case.

    <figure><img src="../../.gitbook/assets/image (151).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
### Only Failed or Inconclusive test cases will have recommended remediations.
{% endhint %}

## Manage Not Run tests

In the case of a **Not run** test case, you have to manually mark it as a **Passed**, **Failed**, or **Inconclusive** test case before you can see a recommended remediation. To do so:

1. From the list of **Not run test cases**, select the specific one you want to investigate.

<figure><img src="../../.gitbook/assets/image (152).png" alt=""><figcaption></figcaption></figure>

2. On the right-hand side pane, you can notice the **Remediations** and **Notes** menus are missing (due to the test case not being run).

<figure><img src="../../.gitbook/assets/image (153).png" alt=""><figcaption></figcaption></figure>

3. Once you run the test **manually** and decide the **status** it should have (Passed/Failed/Inconclusive), you have to manually set up the correct status by using the status **drop down menu** from the top right-hand corner.

<figure><img src="../../.gitbook/assets/image (154).png" alt=""><figcaption></figcaption></figure>

4. If you change the status to **Failed** or **Inconclusive**, the **Remediations** button becomes available on the screen.

<figure><img src="../../.gitbook/assets/image (155).png" alt=""><figcaption></figcaption></figure>

5. You can now **change** the **recommended** **remediation**, if needed or available, as explained [above](access-recommended-remediations.md).
