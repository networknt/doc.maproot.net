---
title: "Create a Restaurant Site"
linktitle: ""
description: ""
godocref: ""
publishdate: ""
lastmod: ""
categories: []
tags: []
weight: 00
slug: ""
aliases: []
toc: false
reviewed: true
---

The following are the steps to create a restaurant site with an online menu. 

* Register a new user as a restaurant owner 

Please fill in the country, province (state), and city in the user profile. For profile location, please refer to [city](/city/)

* Create an entity on the city map

On the entity form, select service as category and restaurant as subcategory. For creating an entity, please refer to [entity](/entity/)

* Create a restaurant site

Once your entity is created on the city map, you can create a restaurant site from the left navigation Website menu. For details, please take a look at the [owner view](/website/restaurant/owner/)

* Access the order system

Once you have the restaurant site up and running, you can send an email to stevehu@gmail.com to add a merchant role to your user profile. Once you have the role, you can see a Merchant Order menu on the left navigation menu.

* Set up Payment Options

If you want to accept online payment through Braintree with credit cards and Paypal, you can create an account at https://www.braintreepayments.com/ and add the merchantId, private key, and public key through the payment menu in the user profile. 

* QR Code for counter or tables

For food courts or restaurants, after your menu is online, you can create a QR code and print it. It can be placed at the counter or on the door of the restaurant. It will direct the online menu for ordering when a user scans the code with their phone. 

The QR code will encode a URL to the online catalog. The following is the URL for a restaurant userId with `restaurant.menu`

```
https://maproot.net/#/app/website?userId=restaurant.menu
```

If you want to add a table number to the order, for example, table2.

```
https://maproot.net/#/app/website?userId=restaurant.menu&instruction=table2
```

This [website](https://www.qr-code-generator.com/) can be used to generate a QR code for URLs. 

