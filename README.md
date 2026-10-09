# Velocity

![Velocity](assets/logo.png)

Manage social publishing from Claude with seven focused workflows: accounts and brands, content calendar, scheduling, editing and cancellation, failed-post recovery, media uploads, and analytics.

## Setup

Install the plugin and connect its Velocity MCP server. Sign in to Velocity and approve access. New customers complete Velocity onboarding and select a plan first. Connect social accounts in Velocity before asking Claude to publish or schedule. Available platforms and features depend on your connected accounts and plan.

## Try it

- Show my brands and connected accounts.
- Show my calendar this week in Eastern time.
- Schedule a post for my selected account, then edit or cancel it.
- Upload an attached image into Velocity.
- Show available analytics and explain a failed post.

When no brand is named, account and calendar views include all authorized brands. Analytics uses the default brand unless another is selected. Claude uses internal references for tools but should show names, handles, captions and readable dates in normal replies.

Publishing is asynchronous: queued does not mean published. Ask for the current status to confirm publication. Confirm the destination account, content and schedule before publishing. The plugin cannot change social passwords or access unauthorized workspaces. Analytics only reports data available in Velocity.

## Data and privacy

The plugin connects only to the production Velocity service at https://www.velocity.li/mcp using OAuth. Its skills do not contain credentials or run local scripts. Tool calls can read your authorized workspace and change posts or upload supplied media. Velocity stores account connections, post content, media and analytics to provide the service, and sends authorized publishing content to the selected social platforms. Retention and deletion are governed by the product privacy policy.

- [Privacy policy](https://www.velocity.li/privacy)
- [Terms](https://www.velocity.li/terms)
- [Support](mailto:support@velocity.li)
- [Website](https://www.velocity.li)

This repository contains the plugin package only. It does not contain Velocity's application backend or customer data.
