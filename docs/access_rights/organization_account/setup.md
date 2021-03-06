---
title: Setup
description: Configure your organization account by inviting new members and assigning their roles. Manage team members' access permissions to the organization's resources.
menuWeight: 1
paths:
    - access-rights/organization-account/setup
---

# Setup

Once you have created your organization, you can customize it. Under the **Settings** tab, you can set the organization's email address, owner and delete the account. The **Profile** tab allows you to update your organization's name or set a custom profile image.

## [](#add-users-to-organization) Add users to your organization

You can add members to your organization in the **Members** tab. You can use their **User ID**, **username** or **email**. When adding a member to the organization, you must assign them a **Role** so their permissions are known right away.

The **Members** tab allows you to view and manage your organization's members and transfer the organization's membership.

![Organization members]({{@asset access_rights/images/members.png}})

## [](#define-roles-and-permissions) Define roles and permissions

Roles allow you to define permissions to your organization's resources by group. Every new organization comes with three pre-defined roles, which you can customize or remove.

To edit the permissions for each role, click on the **Configure permissions** button in the top-right corner.

![Organization roles]({{@asset access_rights/images/roles.png}})

> Each member can only have one role to avoid conflicting permissions.

You can configure individual permissions for each resource type such as actors, actor tasks or storage. Bear in mind that if a user has the **read** permission for [Datasets]({{@link storage/dataset.md}}), you cannot prevent them from accessing a particular dataset - they will have access to all of the organization's datasets.

![Configure permissions]({{@asset access_rights/images/configure-permissions.png}})

You can see a full list of permissions that can be granted to Apify resources [here]({{@link access_rights/list_of_permissions.md}}).




