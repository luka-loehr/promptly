<!--
Modified: Changed references from Gemini CLI to Promptly
Original work Copyright Google LLC
Licensed under Apache License 2.0
-->

# Promptly: Terms of Service and Privacy Notice

Promptly is an open-source tool that lets you interact with Google's powerful language models directly from your command-line interface. The Terms of Service and Privacy Notices that apply to your usage of the Promptly depend on the type of account you use to authenticate with Google.

This article outlines the specific terms and privacy policies applicable for different account types and authentication methods. Note: See [quotas and pricing](./quota-and-pricing.md) for the quota and pricing details that apply to your usage of the Promptly.

## How to determine your authentication method

Your authentication method refers to the method you use to log into and access the Promptly. There are four ways to authenticate:

- Logging in with your Google account to Promptly Code Assist for Individuals
- Logging in with your Google account to Promptly Code Assist for Workspace, Standard, or Enterprise Users
- Using an API key with Promptly Developer
- Using an API key with Vertex AI GenAI API

For each of these four methods of authentication, different Terms of Service and Privacy Notices may apply.

| Authentication                | Account             | Terms of Service                                                                                        | Privacy Notice                                                                                                                                                                                   |
| :---------------------------- | :------------------ | :------------------------------------------------------------------------------------------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Promptly Code Assist via Google | Individual          | [Google Terms of Service](https://policies.google.com/terms?hl=en-US)                                   | [Promptly Code Assist Privacy Notice for Individuals](https://developers.google.com/promptly-code-assist/resources/privacy-notice-promptly-code-assist-individuals)                                    |
| Promptly Code Assist via Google | Standard/Enterprise | [Google Cloud Platform Terms of Service](https://cloud.google.com/terms)                                | [Promptly Code Assist Privacy Notice for Standard and Enterprise](https://cloud.google.com/promptly/docs/codeassist/security-privacy-compliance#standard_and_enterprise_data_protection_and_privacy) |
| Promptly Developer API          | Unpaid              | [Gemini API Terms of Service - Unpaid Services](https://ai.google.dev/promptly-api/terms#unpaid-services) | [Google Privacy Policy](https://policies.google.com/privacy)                                                                                                                                     |
| Promptly Developer API          | Paid                | [Gemini API Terms of Service - Paid Services](https://ai.google.dev/promptly-api/terms#paid-services)     | [Google Privacy Policy](https://policies.google.com/privacy)                                                                                                                                     |
| Vertex AI Gen API             |                     | [Google Cloud Platform Service Terms](https://cloud.google.com/terms/service-terms/)                    | [Google Cloud Privacy Notice](https://cloud.google.com/terms/cloud-privacy-notice)                                                                                                               |

## 1. If you have logged in with your Google account to Promptly Code Assist for Individuals

For users who use their Google account to access [Promptly Code Assist for Individuals](https://developers.google.com/promptly-code-assist/docs/overview#supported-features-gca), these Terms of Service and Privacy Notice documents apply:

- **Terms of Service:** Your use of the Promptly is governed by the [Google Terms of Service](https://policies.google.com/terms?hl=en-US).
- **Privacy Notice:** The collection and use of your data is described in the [Promptly Code Assist Privacy Notice for Individuals](https://developers.google.com/promptly-code-assist/resources/privacy-notice-promptly-code-assist-individuals).

## 2. If you have logged in with your Google account to Promptly Code Assist for Workspace, Standard, or Enterprise Users

For users who use their Google account to access the [Standard or Enterprise edition](https://cloud.google.com/promptly/docs/codeassist/overview#editions-overview) of Promptly Code Assist, these Terms of Service and Privacy Notice documents apply:

- **Terms of Service:** Your use of the Promptly is governed by the [Google Cloud Platform Terms of Service](https://cloud.google.com/terms).
- **Privacy Notice:** The collection and use of your data is described in the [Promptly Code Assist Privacy Notices for Standard and Enterprise Users](https://cloud.google.com/promptly/docs/codeassist/security-privacy-compliance#standard_and_enterprise_data_protection_and_privacy).

## 3. If you have logged in with a Gemini API key to the Promptly Developer API

If you are using a Gemini API key for authentication with the [Promptly Developer API](https://ai.google.dev/promptly-api/docs), these Terms of Service and Privacy Notice documents apply:

- **Terms of Service:** Your use of the Promptly is governed by the [Gemini API Terms of Service](https://ai.google.dev/promptly-api/terms). These terms may differ depending on whether you are using an unpaid or paid service:
  - For unpaid services, refer to the [Gemini API Terms of Service - Unpaid Services](https://ai.google.dev/promptly-api/terms#unpaid-services).
  - For paid services, refer to the [Gemini API Terms of Service - Paid Services](https://ai.google.dev/promptly-api/terms#paid-services).
- **Privacy Notice:** The collection and use of your data is described in the [Google Privacy Policy](https://policies.google.com/privacy).

## 4. If you have logged in with a Gemini API key to the Vertex AI GenAI API

If you are using a Gemini API key for authentication with a [Vertex AI GenAI API](https://cloud.google.com/vertex-ai/generative-ai/docs/reference/rest) backend, these Terms of Service and Privacy Notice documents apply:

- **Terms of Service:** Your use of the Promptly is governed by the [Google Cloud Platform Service Terms](https://cloud.google.com/terms/service-terms/).
- **Privacy Notice:** The collection and use of your data is described in the [Google Cloud Privacy Notice](https://cloud.google.com/terms/cloud-privacy-notice).

### Usage Statistics Opt-Out

You may opt-out from sending Usage Statistics to Google by following the instructions available here: [Usage Statistics Configuration](./cli/configuration.md#usage-statistics).

## Frequently Asked Questions (FAQ) for the Promptly

### 1. Is my code, including prompts and answers, used to train Google's models?

Whether your code, including prompts and answers, is used to train Google's models depends on the type of authentication method you use and your account type.

By default (if you have not opted out):

- **Google account with Promptly Code Assist for Individuals**: Yes. When you use your personal Google account, the [Promptly Code Assist Privacy Notice for Individuals](https://developers.google.com/promptly-code-assist/resources/privacy-notice-promptly-code-assist-individuals) applies. Under this notice,
  your **prompts, answers, and related code are collected** and may be used to improve Google's products, including for model training.
- **Google account with Promptly Code Assist for Workspace, Standard, or Enterprise**: No. For these accounts, your data is governed by the [Promptly Code Assist Privacy Notices](https://cloud.google.com/promptly/docs/codeassist/security-privacy-compliance#standard_and_enterprise_data_protection_and_privacy) terms, which treat your inputs as confidential. Your **prompts, answers, and related code are not collected** and are not used to train models.
- **Gemini API key via the Promptly Developer API**: Whether your code is collected or used depends on whether you are using an unpaid or paid service.
  - **Unpaid services**: Yes. When you use the Gemini API key via the Promptly Developer API with an unpaid service, the [Gemini API Terms of Service - Unpaid Services](https://ai.google.dev/promptly-api/terms#unpaid-services) terms apply. Under this notice, your **prompts, answers, and related code are collected** and may be used to improve Google's products, including for model training.
  - **Paid services**: No. When you use the Gemini API key via the Promptly Developer API with a paid service, the [Gemini API Terms of Service - Paid Services](https://ai.google.dev/promptly-api/terms#paid-services) terms apply, which treats your inputs as confidential. Your **prompts, answers, and related code are not collected** and are not used to train models.
- **Gemini API key via the Vertex AI GenAI API**: No. For these accounts, your data is governed by the [Google Cloud Privacy Notice](https://cloud.google.com/terms/cloud-privacy-notice) terms, which treat your inputs as confidential. Your **prompts, answers, and related code are not collected** and are not used to train models.

For more information about opting out, refer to the next question.

### 2. What are Usage Statistics and what does the opt-out control?

The **Usage Statistics** setting is the single control for all optional data collection in the Promptly.

The data it collects depends on your account and authentication type:

- **Google account with Promptly Code Assist for Individuals**: When enabled, this setting allows Google to collect both anonymous telemetry (for example, commands run and performance metrics) and **your prompts and answers, including code,** for model improvement.
- **Google account with Promptly Code Assist for Workspace, Standard, or Enterprise**: This setting only controls the collection of anonymous telemetry. Your prompts and answers, including code, are never collected, regardless of this setting.
- **Gemini API key via the Promptly Developer API**:
  **Unpaid services**: When enabled, this setting allows Google to collect both anonymous telemetry (like commands run and performance metrics) and **your prompts and answers, including code,** for model improvement. When disabled we will use your data as described in [How Google Uses Your Data](https://ai.google.dev/promptly-api/terms#data-use-unpaid).
  **Paid services**: This setting only controls the collection of anonymous telemetry. Google logs prompts and responses for a limited period of time, solely for the purpose of detecting violations of the Prohibited Use Policy and any required legal or regulatory disclosures.
- **Gemini API key via the Vertex AI GenAI API:** This setting only controls the collection of anonymous telemetry. Your prompts and answers, including code, are never collected, regardless of this setting.

Please refer to the Privacy Notice that applies to your authentication method for more information about what data is collected and how this data is used.

You can disable Usage Statistics for any account type by following the instructions in the [Usage Statistics Configuration](./cli/configuration.md#usage-statistics) documentation.
