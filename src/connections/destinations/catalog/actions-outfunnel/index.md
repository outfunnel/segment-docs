---
title: Outfunnel Destination
hide-boilerplate: true
hide-dossier: true
id: 5f7dd8191ad74f868ab1fc49
---

{% include content/plan-grid.md name="actions" %}

[Outfunnel](https://outfunnel.com/product-led-sales-platform/?utm_source=segmentio&utm_medium=docs&utm_campaign=partners) is a product-led sales platform that syncs product usage insights to CRMs like Pipedrive so your salespeople can easily find product-qualified leads and close more revenue.

This destination is maintained by Outfunnel. For any issues with the destination, [contact their Support team](mailto:support@outfunnel.com).

Outfunnel’s Segment integration is an [Actions-based Destination in cloud mode](https://segment.com/docs/connections/destinations/#connection-modes)
 that lets you send your frontend and backend events directly to Outfunnel.

{% include content/ajs-upgrade.md %}

{% include content/beta-note.md %}

## Benefits of Outfunnel
Outfunnel provides the following benefits

- **Easy mapping of data**.  Outfunnel allows you to map Segment and CRM properties and chosoe which events you'd like to sync to your CRM.
- **Fast no-code setup**. Set up the sync in minutes without writing a line of code.

## Getting started

> info ""
> Before you begin, get the API key and User ID in Outfunnel Integrations section which you’ll need to use to configure the integration.

1. From the Segment web app, click **Catalog**, then click **Destinations**.
2. Find the Destinations Actions item in the left navigation, and click it.
3. Click **Configure Outfunnel**
4. Select an existing Source to connect to Outfunnel (Actions).
5. Enter your Outfunnel API key and User ID in the respective fields


Once the installation is complete, log in to your application and do an activity that triggers an event to Segment. You should then see this event in Outfunnel.

{% include components/actions-fields.html %}
