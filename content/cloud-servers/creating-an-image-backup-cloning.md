---
permalink: creating-an-image-backup-cloning/
audit_date:
title: Create an image backup (cloning)
type: article
created_date: '2013-02-12'
created_by: Renee Rendon
last_modified_date: '2018-09-05'
last_modified_by: Shaun Crumpler
product: Cloud Servers
product_url: cloud-servers
---

**Note: Creating an image of a server is possible on General Purpose and Standard server flavors. For boot-from-volume flavors, 
the block storage volume needs to be backed up by using snapshots or Cloud Backup.** 

This article guides you through the process of creating an image backup (cloning).

While you can create a different size server from that of the saved image, you must still use the same base OS
version.

The first part of the procedure takes you through creating a snapshot image; if your snapshot image has already
been created, you can skip to Restoring a Server from a saved image.

1. Log into the [Cloud Control Panel](http://mycloud.rackspace.com).

2. Select the server that you want to clone by clicking the actions cog
to the left of the server name. From the drop-down menu, click **Create Image**.

   A pop-up window will appear that allows you to name the image.

3. After naming the image, click **Create Image**.

Server images will appear in the **Images** list after they have been created. They can be accessed by clicking on the **View Images** in the **Images** section.
