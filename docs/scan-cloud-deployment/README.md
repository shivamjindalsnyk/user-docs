# Scan cloud configurations

With Snyk, you can secure cloud infrastructure configurations before and after it is deployed. [Snyk Infrastructure as Code (IaC)](snyk-infrastructure-as-code/) enables you to develop secure cloud infrastructure, and [Snyk Cloud](snyk-cloud/) helps you keep your cloud environment secure.

{% hint style="info" %}
**Feature availability**\
Integrated Infrastructure as Code (IaC) is a new version of Snyk IaC that secures cloud configurations across the entire SDLC, from code to deployed cloud environments. Integrated IaC is currently in closed beta. Please reach out to your account team with any questions.
{% endhint %}

* Scan [IaC](snyk-infrastructure-as-code/) and [cloud](snyk-cloud/) resources for misconfigurations using a comprehensive set of security rules.
* [Fix Cloud issues](snyk-cloud/integrated-infrastructure-as-code/fix-cloud-issues-in-iac.md) directly in the IaC source code that was used to deploy the misconfigured Cloud resources, by linking a Cloud issue to the underlying IaC template via a SCM source code link.
* Receive [fix advice](snyk-infrastructure-as-code/getting-started-snyk-iac.md) so you can make changes directly to code, before applications reach production.
* Suppress false positives in IaC tests by applying [context from deployed infrastructure](snyk-cloud/integrated-infrastructure-as-code/adding-cloud-context-to-your-iac-test.md).
* [Detect drift](snyk-infrastructure-as-code/detect-drift-and-manually-created-resources/) and manually created resources in your cloud.
* Inspect every [cloud resource's configuration](snyk-cloud/snyk-cloud-issues/view-cloud-issues-in-the-snyk-web-ui.md) at a given moment in time, and see the attributes that caused an issue.
* [Filter issues](snyk-cloud/snyk-cloud-issues/) to target the most mission-critical resources.
* Review a [report of issues](../manage-issues/reports/next-gen-reporting/available-snyk-reports.md#cloud-compliance-issues-report) for an entire organization, organized by compliance standard.

For a list of supported IaC environments and cloud providers, see [Supported providers - IaC and Cloud](supported-providers-iac-and-cloud.md).
