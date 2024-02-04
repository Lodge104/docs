---
title: Documentation Center
description: 
published: true
date: 2024-02-04T17:20:18.388Z
tags: 
editor: markdown
dateCreated: 2024-02-04T17:20:18.387Z
---

# Renewing SSL
The certificate for the documentation site is provided by the non-profit Lets Encrypt. By design it expires every 3 months and must be renewed manually. Follow these steps to renew the certificate.
## Renewal Steps
1. Visit the SSL page in the admin panel.
2. Turn off auto redirect to HTTPS.
3. Visit the same page using http.
4. Click the request a new certificate button.
5. Turn on auto redirect to HTTPS.
6. Refresh the page and check that you're using the new certificate using the browser's certificate tool.