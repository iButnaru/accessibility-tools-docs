---
description: >-
  Environments represent distinct instances of the website that you want to
  test, each serving a specific purpose in the development lifecycle.
---

# 🌐 Environments

You can maintain separate environments, which enables you to build, test, and deploy changes systematically while minimizing risks to end users. Accessibility Tools comes with the following predefined environments:

* **Local**—For individual development work.
* **Development**—For team integration and initial testing.
* **Staging**—For pre-production validation and user acceptance testing.
* **Production**—For the live application that serves real users.

Each environment maintains its own configuration, data, and access controls, creating a structured pathway from initial code changes to public release. Environments are used when creating a project. For more information, see [Create a project](../projects/create-a-project.md).

### View existing environments

To access and view **existing environments**, on the left-hand side navigation pane, go to _**Settings >  Environments**_.

<figure><img src="../../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

The environments in the above picture are standard and cannot be changed. You can only tick/clear the check box next to the desired environment, to make sure the specific environment is included/excluded when [creating a project](../projects/create-a-project.md).

### Create an environment

To create an environment:

1. On the left-hand side navigation pane, go to ![](<../../.gitbook/assets/image (12).png>)_**Settings >  Environments**_ and click ![](<../../.gitbook/assets/image (28).png>) **Add environment**.
2. In the **Add environment** wizard screen, give your environment a meaningful name.

<figure><img src="../../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

When finished, click **Create**.

Once created, the **new environment** becomes available in the environments list, with the **Type** marked as **Custom**:

<figure><img src="../../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

### Modify the name of an environment

To modify the name of an environment:

1. On the left-hand side navigation pane, go to ![](<../../.gitbook/assets/image (12).png>)_**Settings >  Environments**_.
2. Click the ![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXe8ogTV-782eGFQGI3UNbBK6CyPOhBDbhApxZwihyDrG0n8IxToMBEVk92GFtQRsTapnYIo3l4BhMUjwafpcHrAIlq_zJardfjBTmlq-Aqs4G1Q_R_fM5zYlydYAcYdZnEQCyqN?key=_EQKB1eDe9ecbVZeBDg4Tw) **Settings** button next to the environment that you want to modify and then **Edit environment** in the shortcut menu.

<figure><img src="../../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

4. In the **Edit environment** screen, rename your custom environment.
5. When finished, click **Save**.

{% hint style="info" %}
You can only modify user created environments, not the standard, built-in ones.
{% endhint %}

### Delete an environment

To delete an environment:

1. On the left-hand side navigation pane, go to ![](<../../.gitbook/assets/image (12).png>)_**Settings >  Environments**_.
2. Click the ![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXe8ogTV-782eGFQGI3UNbBK6CyPOhBDbhApxZwihyDrG0n8IxToMBEVk92GFtQRsTapnYIo3l4BhMUjwafpcHrAIlq_zJardfjBTmlq-Aqs4G1Q_R_fM5zYlydYAcYdZnEQCyqN?key=_EQKB1eDe9ecbVZeBDg4Tw) **Settings** button next to the environment that you want to delete. On the shortcut menu, click **Delete environment**.

<figure><img src="../../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

4. In the **confirmation** screen, tick the _"Yes, I'm sure"_ box, then click **Delete**.

<figure><img src="../../.gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>

Your custom environment has now been deleted and is no longer available in the list

<figure><img src="../../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
You can only delete user created environments, not the standard, built-in ones.
{% endhint %}
