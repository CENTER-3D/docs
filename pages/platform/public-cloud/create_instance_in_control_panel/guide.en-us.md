---
title: 'Create an instance in your OVHcloud customer account'
slug: create_an_instance_in_your_ovh_customer_account
excerpt: 'This guide will show you how to create an instance in your Public Cloud account.'
legacy_guide_number: g1775
section: 'Getting started'
---

**Last updated 30th March 2021**

## Objective

You can use the OVHcloud [Public Cloud](https://www.ovhcloud.com/en/public-cloud/) to create instances (i.e. virtual servers) quickly and easily, in just a few clicks.

**Find out how to create an instance in the OVHcloud Public Cloud Control Panel.**

## Requirements

* access to the [OVHcloud Control Panel](https://ca.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com/world/&ovhSubsidiary=we){.external}
* a [Public Cloud](https://www.ovhcloud.com/en/public-cloud/){.external} project created in your OVHcloud account
* an SSH key created in the OVHcloud Control Panel

### Deploy a Public Cloud Instance

In order to deploy a public cloud instance, log in to the [OVHcloud Control Panel](https://ca.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com/world/&ovhSubsidiary=we){.external}. Click `Public Cloud`{.action} in the top-left corner of the page. Then, on the following screen, click the arrow button next to your default project name in the top-left corner of the screen. Now select the project on which you would like to create a new instance.

![select_project](images/select_project.png){.thumbnail}

Once you have selected the correct project, click the `Instances`{.action} button under the "Compute" section on the left-hand sidebar.

![create_instance](images/create_instance.png){.thumbnail}

Next, click the `Create an instance`{.action} button. You will be taken to the following menu where you can select the instance you would like to create.

![create_instance1](images/create_instance1-2021.png){.thumbnail}

The table below gives a brief explanation of the differences between the types of instances:

| Server Type | Guaranteed Resources | Usage notes |
| :---         |     :---:      |          :--- |
| General Purpose   | ✓     | Development servers, web or business applications    |
| CPU     | ✓       | Video encoding or other high-performance computing      |
| RAM   | ✓     | Databases, analysis, and in-memory calculations    |
| GPU     | ✓       | Massively parallel processing power for specialised applications (rendering, big data, deep learning, etc.)       |
| Sandbox    | -       | Hosted on shared resources for testing and development environments      |
| Discovery    | -       | Hosted on shared resources for testing and development environments      |
| IOPS   | ✓     | Optimised for disk data transfer    |

> [!primary]
>
You will initially be limited to 20 instances, 20 vCores and 40GB of RAM across any given project. An increase in the resource limit may be requested by [submitting a ticket](https://www.ovh.com/manager/dedicated/index.html#/ticket){.external} to our Customer Support team.
>


Follow the menu to select the region in which you would like your public cloud instance to be located. The third option is where you select your OS.

> [!primary]
>
If a Windows OS is selected, then a licence will automatically be provisioned and you will be billed monthly for it.
>

![install](images/os_install.png){.thumbnail}

> [!primary]
>
Public cloud instances running a Unix-based OS require an SSH key to be added to the server. For more information on generating an SSH key, please check out our [Create SSH Keys](../create-ssh-keys/){.external} article.
>

In the fourth part of the menu, you can choose the number of instances to create, name your instance, and add a private network or post-installation script, should you choose to do so.

![add an instance](images/configure_instance.png){.thumbnail}

Finally, choose whether you would like to be billed monthly or hourly.

> [!warning]
>
>If you choose to be billed hourly, you will continue to be billed as long as the instance exists. It does not matter if the instance is currently in use or not.
>


Once you have confirmed that all of the information you have entered is correct, click the `Create an instance`{.action} button to finish creating your new instance. Your instance may take a few minutes to provision.

### Conclusion

Having read this article, you should be able to provision an instance on your public cloud project via the OVHcloud Control Panel. For further reading about what you can do with your instance, please check out our articles on the [Public Cloud Services](../){.external} documentation page.

## Go further

[Creating and connecting to your first Public Cloud instance](../public-cloud-first-steps/)

Join our community of users on <https://community.ovh.com/en/>.
