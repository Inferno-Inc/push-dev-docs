---
description: Understanding the concept of Delegated Notifications.
---

# What are Delegated Notifications?

## Delegated Notifications

Delegated notifications is a feature that allows channel owners to delegate their power of sending notifications to any other wallet address or multiple wallets of their choice.

Once approved by the channel owner, a wallet address can send notifications on behalf of the channel to its subscribers. The channel owner can, however, revoke the approval at any given time.

This mechanism of sending delegated notifications is quite effective in providing value-added services to the channels. It also ensures the availability of mechanisms that can be used by EPNS or any other third-party infrastructure to send on-chain notifications on the channel’s behalf.

The channel owner can trigger the above-mentioned functions to either allow or remove an address as a valid notification sender. Once allowed, the specific address(es) can also send notifications on behalf of the channel.

{% hint style="info" %}
**Note:** _Adding a delegate notification sender doesn't remove the ability of the channel maintainer to send notifications._&#x20;

_They can keep on sending notifications as well as the delegate notification sender which will always be shown as coming from the same channel._
{% endhint %}

##
