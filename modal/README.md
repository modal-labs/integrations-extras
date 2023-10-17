# Modal

## Overview

[Modal][1] lets you run generative AI models, large-scale batch jobs, job
queues, and much more. The Datadog integration collects logs and metrics from
your applications for you to observe directly in your Datadog account.

## Setup

### Installation

To set up the Modal integration:

1. Go to your [Datadog Integrations page][2], search for the **Modal** tile and
   click **Install Integration**.

2. Click **Connect Accounts** to begin authorization of this integration. You
   will be redirected to log into [Modal][1], and once logged in, you'll be
   redirected to the Datadog authorization page.

3. Click the **Authorize** button to complete setup.

Logs and metrics from your Modal apps should now start appearing in Datadog.

## Data Collected

### Metrics

Modal collects utilization metrics for applications/functions run on Modal --
you can currently view them on your [Modal][1] dashboard directly. We're
working on surfacing this to Datadog shortly.

### Logs

Modal collects both audit logs and application logs, both accessble through
your [Modal][1] dashboard. Audit logs are currently accessible through Datadog
as well. We're working on surfacing application logs through shortly.

### Events

Modal does not include any events.

## Uninstallation

Once this integration has been uninstalled, any previous authorizations are
revoked and logs/metrics are 

1. Go to your [Datadog Integrations page][2], search for the **Modal** tile and
   click **Uninstall Integration** in the **Configure** tab.

2. Ensure that all API keys associated with this integration have been disabled
   by searching for the integration name on the [API Keys page][4].

Your Modal application logs and metrics will no longer be sent to Datadog.

## Troubleshooting

Need help? Contact [Modal support][3].

[1]: https://modal.com
[2]: https://app.datadoghq.com/integrations
[3]: mailto:support@modal.com
[4]: https://app.datadoghq.com/organization-settings/api-keys?filter=Modal

