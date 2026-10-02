---
description: >-
  Depending on their nature and the issue they address, in Accessibility Tools,
  remediations are grouped into manageable categories.
---

# 🧰 Remediation categories

In Accessibility Tools, compliance remediations are grouped into specific logical categories, based on the test targets they remediate, for easier administration. For example, remediation categories can be related to ARIA, CSS, HTML, SMIL and so on. You can view existing Remediation categories, and also create new ones, modify, and delete them.

## View and manage standard remediation categories

There are several actions you can run on standard, built-in remediation categories:

* To access and view existing remediation categories, on the left-hand side navigation pane, go to ![](<../../.gitbook/assets/image (12).png>)_**Settings > Remediation categories**_ to view the standard remediation categories. You can also add your own, custom remediation categories.
* To include/exclude remediation categories into/from tests, tick/clear the respective checkboxes next to the desired remediations.

<figure><img src="../../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

* To re-prioritize remediations, change the order in which remediation categories are displayed on the screen. This list determines the order in which the tests take the remediation categories into account. As some tests can have multiple remediations, reordering this list will change the way remediations are applied to your tests. In order to change the priorities, simply click the ![](<../../.gitbook/assets/image (36).png>)drag button on the left-hand side of the line you need to move and drop it on the desired position.

<figure><img src="../../.gitbook/assets/image (37).png" alt=""><figcaption></figcaption></figure>

In the example above, we have moved the CSS category above the ARIA, which will have any CSS remediations take precedence in relation to tests that would have remediations from both category.

## Create a remediation category

To create a remediation category:

1. On the left-hand side navigation pane, go to  ![](<../../.gitbook/assets/image (12).png>)_**Settings >  Remediation categories**_ and click the ![](<../../.gitbook/assets/image (39).png>) **Add category** button.
2. In the **Add remediation category** screen, give your new category a meaningful name.

<figure><img src="../../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

When finished, click **Create**.&#x20;

Your new customer remediation category is displayed at the bottom of the list by default, but you can easily [reposition](remediation-categories.md#view-and-manage-standard-remediation-categories) it, as desired.&#x20;

<figure><img src="../../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

## Modify the name of a remediation category

To modify the name of a remediation category:

1. On the left-hand side navigation pane, go to  ![](<../../.gitbook/assets/image (12).png>)_**Settings >  Remediation categories**_.
2. Click the ![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXe8ogTV-782eGFQGI3UNbBK6CyPOhBDbhApxZwihyDrG0n8IxToMBEVk92GFtQRsTapnYIo3l4BhMUjwafpcHrAIlq_zJardfjBTmlq-Aqs4G1Q_R_fM5zYlydYAcYdZnEQCyqN?key=_EQKB1eDe9ecbVZeBDg4Tw) **Settings** button next to the desired remediation category and click **Edit category** on the shortcut menu.

<figure><img src="../../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

3. In the **Edit remediation category** screen, rename your category. \
   When finished, click **Save**.

<figure><img src="../../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
You can only rename custom, user-created remediation categories.
{% endhint %}

## Delete a remediation category

To delete a remediation category:

1. On the left-hand side navigation pane, go to  ![](<../../.gitbook/assets/image (12).png>)_**Settings >  Remediation categories**_.
2. Click the ![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXe8ogTV-782eGFQGI3UNbBK6CyPOhBDbhApxZwihyDrG0n8IxToMBEVk92GFtQRsTapnYIo3l4BhMUjwafpcHrAIlq_zJardfjBTmlq-Aqs4G1Q_R_fM5zYlydYAcYdZnEQCyqN?key=_EQKB1eDe9ecbVZeBDg4Tw) **Settings** button next to the desired remediation category and click **Delete category** on the shortcut menu.

<figure><img src="../../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

3. In the confirmation screen, tick the _"Yes, I'm sure"_ box and click **Delete**.

<figure><img src="../../.gitbook/assets/image (44).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
You can only delete custom user-created remediation categories. If you haven't created custom remediations categories, the **Delete** button will not be available in the settings menu.
{% endhint %}
