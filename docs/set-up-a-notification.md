---
title: "Set up a notification"
verified: "verified against the running product 2026-09-05T12:38:46.480Z"
---

# Set up a notification

Add a webhook notification channel in Uptime Kuma so your monitors can post alerts to an endpoint you choose.

## Before you start

Open Settings and go to the Notifications tab at /settings/notifications, where notification channels for your monitors are listed.

## Step 1: Click Setup Notification to open the notification dialog.

![Screenshot 1](./images/set-up-a-notification-1.png "asset:cmtoaygmk000dnpcgl4k6w0sd")

## Step 2: In the notification type list, choose Webhook. The form switches to show the webhook fields.

![Screenshot 2](./images/set-up-a-notification-2.png "asset:cmtoayhfb000enpcghbrp4xop")

## Step 3: In Friendly Name, enter a name for this notification channel. The recording uses "TJ T38 livei5dzz8-3", but you can use your own name.

![Screenshot 3](./images/set-up-a-notification-3.png "asset:cmtoayiv0000gnpcg6jw65ndl")

## Step 4: In Post URL, enter the endpoint that should receive the webhook. The recording uses "http://host.docker.internal:3100"; enter your own endpoint URL.

![Screenshot 4](./images/set-up-a-notification-4.png "asset:cmtoaykas000inpcgixv5fyh0")

## Step 5: In the request body list, choose Preset - application/json to send the ready-made JSON payload.

![Screenshot 5](./images/set-up-a-notification-5.png "asset:cmtoayl0a000jnpcgec7n1od7")

## Step 6: Click Save to store the webhook notification.

![Screenshot 6](./images/set-up-a-notification-6.png "asset:cmtoaylu2000knpcgwdgf4neh")

## Observed result

The recording does not show a confirmed result.

## About this page

Written from a completed recording. The instructions describe recorded actions and visible results.

## Related pages

Find your way around Uptime Kuma

Pause a Monitor in Uptime Kuma
