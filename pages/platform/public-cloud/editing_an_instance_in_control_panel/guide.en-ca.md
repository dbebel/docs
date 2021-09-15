---
title: Edit an instance
slug: edit-an-instance
excerpt: Find out how to edit your instance from the OVHcloud Control Panel
legacy_guide_number: 1778
section: Management via Control Panel
order: 5
---

**Last updated 15th September 2021**

## Introduction

Following an increase in activity, or simply new needs, it is possible that your instance cannot meet this new load due to a lack of resources. However, with the Public Cloud, you can increase the resources available to your instance with just a few clicks.

**This guide explains how to resize your instance via the OVHcloud Control Panel**

> [!alert]
> Only upscaling is possible for classic models. This will also cause the instance to be shut down for the duration of the process.
>

> [!success]
> Flex instances allow resizing to higher or lower models with a single disk size.
>

## Requirements

- an [OVHcloud Public Cloud instance](../create_an_instance_in_your_ovh_customer_account/)
- access to the [OVHcloud Control Panel](https://ca.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com/ca/en/&ovhSubsidiary=ca){.external}

## Instructions

### Editing the instance

Log in to the [OVHcloud Control Panel](https://ca.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com/ca/en/&ovhSubsidiary=ca), click on the `Public Cloud`{.action} section menu, then click on the `Instances`{.action} in the left side menu.

![Click Instance name](images/instancename.png){.thumbnail}

Click on the instance name to edit and click on `Edit`{.action} in the dashboard.

![Edit instance](images/editinstance.png){.thumbnail}

### Instance name and image

This section allows you to edit the instance name and image.

![Change name or image](images/editnameorimage.png){.thumbnail}

> [!alert]
> If you select a different image, all of the data stored on the instance will be deleted, this action is irreversible. It is also not possible to switch from a linux image to a windows image and vice versa.
>

### Template 

This section allows you to select a new template for your instance. 

![Edit template](images/edittemplate.png){.thumbnail}

> [!warning]
> Depending the quota(resources) you have left on your project, certain templates will not be available. In such cases, you will need to [contact our support](https://help.ovhcloud.com/en-ca/contact-method/) team by creating a ticket from your Control Panel to find out if you are eligible for a quota increase.
>

### Instance type and billing period

This section allows you to modify your billing period or to switch your instance to the flex option if needed. Find out more about changing the billing rate for your Public Cloud instance [here](https://docs.ovh.com/ca/en/public-cloud/change-public-cloud-billing-rate/).

![Edit billing or instance](images/optionandbilling.png){.thumbnail}

Apply the changes once the selection is done, the instance will be rebooted during the operation.


## Go further

Join our community of users on <https://community.ovh.com/en/>.