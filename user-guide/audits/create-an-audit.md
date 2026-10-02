---
description: Step-by-step instructions on how to create an audit.
---

# 📁 Create an audit

To create an audit:

1. On the left-hand side navigation pane, click ![](<../../.gitbook/assets/image (141).png>) **Audits** and then click the ![](<../../.gitbook/assets/image (130).png>) **New audit** button.

<figure><img src="../../.gitbook/assets/image (129).png" alt=""><figcaption></figcaption></figure>

2. In the **Add audit** wizard screen, fill in the details:<br>

<figure><img src="../../.gitbook/assets/image (131).png" alt=""><figcaption></figcaption></figure>

* **Audit type**: Select the desired framework of compliance and accessibility standards and guidelines. Read more about Audit types [here](types-of-audits.md).
* **WCAG Version**: Select the desired WCAG version that you want your audit to be based on.
* **Conformance target**: Select the desired conformance target of your new audit, from lowest (A) to highest (AAA).
* **Report Identifier**: This field is for internal use and can include a given ID, version number, date, or any identifier you wish to add to it so you can reference it later.
* **Report Date**: Select the desired export date from the calendar.

When finished, click **Continue**.

2. In the next wizard screen, select the WCAG conformance level that you want your audit to include besides the one that you selected in the **Conformance target** field in the first step. The options are:\
   \- **Level A** - Basic accessibility (minimum level)\
   \- **Level AA** - Standard accessibility (legal requirement in most jurisdictions)\
   \- **Level AAA** - Enhanced accessibility (highest level, often impractical for entire websites).&#x20;

When finished, click **Continue**.

{% hint style="info" %}
You can select any extra conformance levels if you need to for this specific audit.&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/image (132).png" alt=""><figcaption></figcaption></figure>

3.  In the next wizard screen, fill in the fields related to the project and the product.

    <figure><img src="../../.gitbook/assets/image (133).png" alt=""><figcaption></figcaption></figure>

* **Project**: Select (if applicable) the project for this audit.
* **Environment type**: This list is automatically populated based on the selected project. However, if the same project was created on multiple environments, select the environment for which you want the audit to be performed.
* **Test**: Select (if applicable) the test instance on which the audit will be applied.

<figure><img src="../../.gitbook/assets/image (134).png" alt=""><figcaption></figcaption></figure>

In the **Product information** section, fill in the optional details that will be populated in the actual audit report that results from running the audit, such as Product name, version, description and website URL.

<figure><img src="../../.gitbook/assets/image (135).png" alt=""><figcaption></figcaption></figure>

Scrolling even further in this step of the **Add audit** screen, you will find the **Vendor information** section, which, similar to the **Product information** section, contains optional details that can be part of the audit report generated at the end of the audit. These details refer to the owner of the product you are auditing like company name, address, website, and contact information.

\
When finished, click **Continue**.

<figure><img src="../../.gitbook/assets/image (136).png" alt=""><figcaption></figcaption></figure>

4. In the **final step** of the Add audit wizard, you will be able to select the **profile of the evaluator** (information that will also appear in the audit report).&#x20;

{% hint style="warning" %}
If a profile is not available at this point, you will have to create one, as this is mandatory information required for the audit report. You can follow the create profile steps through the Add audit wizzard or use the [Profiles](../settings/user-profiles.md) menu (under Settings) to do so before starting a new audi
{% endhint %}

5. Next, after the evaluator profile is selected, the fields under **Evaluation** are optional and will appear in the audit report generated at the end of an audit:<br>

* **Notes**: Any necessary comments that you need included in the overview of your audit report
* **Evaluation methods used**: note any specific methods that you need noted in the report
* **Legal disclaimer**: This will appear at the end of the audit report and can be added if and when needed
* **Repository**: add the URL for your project
* **Feedback**: Note any input provided by the Evaluator
* **License**: Note the Licence type

<figure><img src="../../.gitbook/assets/image (137).png" alt=""><figcaption></figcaption></figure>

6.  At the bottom of the screen, the **Executive summary** field contains a **summary** of the report that is provided by the **Evaluator**.<br>

    <figure><img src="../../.gitbook/assets/image (138).png" alt=""><figcaption></figcaption></figure>

When finished, click **Create**.&#x20;

Your newly-created audit is displayed.

<figure><img src="../../.gitbook/assets/image (140).png" alt=""><figcaption></figcaption></figure>

<br>
