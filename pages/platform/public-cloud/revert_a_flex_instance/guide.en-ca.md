---
title: Reverting a flex instance
slug: revert-a-flex-instance
legacy_guide_number: 1773
excerpt: Find out how to revert a flex instance from the Horizon interface
section: Horizon
order: 7
---

**Last updated 15th September 2021**

## Objective

A flex instance is a single size disk (50GB) instance which offers a faster process for snapshots. It allows resizing to higher or lower models with a fix storage space whereas classic models can only be resized to higher models. As your infrastructure is constantly evolving, you may need to resize your instance as well as the storage space. In this case, you will need to «revert» your flex instance to a classic model. This action can only be done from the Horizon interface.

**This guide shows you how to resize your flex instance from the OpenStack Horizon interface.**

## Requirements

- a flex [OVHcloud Public Cloud instance](../create_an_instance_in_your_ovh_customer_account/) 
- [Create an access to the Horizon interface](https://docs.ovh.com/ca/en/public-cloud/configure_user_access_to_horizon/)

## Instructions

Log into the [Horizon interface](https://horizon.cloud.ovh.net/auth/login/), and make sure you are in the correct region. You can verify this on the top left corner. Next, click on the `Compute`{.action} menu on the left side and select `Instances`{.action}. Select `Resize Instance`{.action} in the drop list for the corresponding instance.

![Resize instance](images/resizeinstance.png){.thumbnail}

This section allows you to select the new instance «flavor» or «model». In our example, our instance is a «b2-15-flex» model and we want to upgrade it to a «b2-30» classic model.

> [!warning] 
> Please note that you can only switch from a linux model to another linux model or from a windows model to another windows model.
>

![Choose new flavor](images/confirmflavor.png){.thumbnail}

To continue, click on the `Resize`{.action} button.

Once the process is completed, you will have a classic instance and a larger storage space.

![New flavor applied](images/newflavor.png){.thumbnail}

In case you wish to revert back to a flex model, you can do this by performing the same steps mentioned above and select a flex «flavor» instead. Alternatively, you can [edit the instance](https://github.com/ovh/docs/blob/JF-PCI-edit-an-instance/pages/platform/public-cloud/editing_an_instance_in_control_panel/guide.en-ca.md) back in the OVHcloud Control Panel.

## Go further

Join our community of users on <https://community.ovh.com/en/>.