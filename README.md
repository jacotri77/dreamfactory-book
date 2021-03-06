---
sidebar: auto
---

# Getting Started with DreamFactory

Welcome to the DreamFactory platform! Whether you’re an open source user, or a paid customer taking advantage of DreamFactory’s advanced capabilities, we wrote this guide to help you begin incorporating the platform into your organization in the most efficient way possible.

::: warning
This guide is under heavy development, with two of a projected seven chapters complete as of September 25. We estimate a new chapter will be completed every few days, so be sure to check back regularly for updates!
:::

## About this Guide

This guide consists of seven chapters, covering the following topics:

### [Chapter 1. Introducing REST and DreamFactory](docs/chapter01.md)

So why would you want to use the DreamFactory platform in the first place? It’s likely because even world class developers and administrators are faced with ever-increasing complexity due in large part to the extraordinary number of internal and third-party data sources which must be integrated with mobile and web applications, ERP solutions, and myriad other services. In this chapter you’ll learn how DreamFactory can bring order to this chaos by introducing silo breaking capabilities to your enterprise, offering a platform for which not only can you auto-generate the APIs used to connect to these data sources, but also secure and monitor them. 

### [Chapter 2. Installing and Configuring DreamFactory](docs/chapter02.md)

Much of the DreamFactory platform is open source, with the code made available via GitHub. But this doesn’t mean you have to be a command-line wizard to begin generating APIs in a flash. In this chapter you’ll learn how to install and configure DreamFactory regardless of your operating system or experience level. We’ll also talk about configuring DreamFactory to suit your specific needs, and highlight key configuration changes which will make your life much easier.

### [Chapter 3. Generating a Database-backed API](docs/chapter03.md)

After installing your DreamFactory instance, it’s only natural to want to see what the platform can do. For most users, this means generating a database API, because the advantages of doing so are so evident. By merely supplying a set of authentication credentials, DreamFactory will generate an API for any of an array of popular databases, including MySQL, SQL Server, Oracle, PostgreSQL, MongoDB, and others. Once generated, you’ll be able to issue REST calls to carry out record creation, retrieval, modification, and deletion tasks. You’ll also be able to perform advanced queries using the REST API, including filters, grouping, joins, limiting, and more. 

### Chapter 4. Authenticating and Monitoring Users

From the moment your API is generated, rest assured it is protected by at minimum a complicated API key. However this represents only the beginning in terms of your options regarding securing an API. You can use DreamFactory's user authentication and authorization features to provide user-specific login via a variety of authentication solutions, including basic auth, LDAP, Active Directory, and SSO. In this chapter you'll learn all about these solutions, and additionally learn how to use DreamFactory's rate limiting and logging capabilities to closely monitor request volume and behavior.

### [Chapter 5. Generating a SOAP-to-REST API](docs/chapter05.md)

The SOAP Protocol has long been instrumental to network-based data exchange, however over time REST has slowly gained influence within enterprises, with many DreamFactory users seeking to supplant their SOAP services with a REST-based solution.

### Chapter 6. Integrating Business Logic

The DreamFactory team regularly works with customers around the globe to build highly customized services based atop our platform. Most often this involves using DreamFactory’s scripting feature, which allows you to write custom code used to validating input parameters, call other APIs, and much, much more.

### Chapter 7. Monetizing Your APIs using Limiting and Logging

You've taken months if not years to amass and curate a valuable data set, and now it is time to monetize it. In this chapter you'll learn how to use DreamFactory's API limiting and logging capabilities to assign and monitor access to your restricted APIs.

### [Chapter 10. Production Best Practices](docs/chapter10.md)

While DreamFactory is already fairly fast, secure and maintenance free out of the box, there are quite a few modifications you can make to enhance your instance.  We have broken these down into several categories to make focusing on individual features easier, almost as a checklist.

## More Ways to Learn

### Videos

Dozens of videos are available via the [DreamFactory Youtube channel](https://www.youtube.com/user/dreamfactorysoftware/videos).

### The DreamFactory Forum

Volunteers and DreamFactory staff alike regularly patrol our [community forum](http://community.dreamfactory.com/). If Stack Overflow is preferred, be sure to tag the question using the [dreamfactory](https://stackoverflow.com/questions/tagged/dreamfactory) tag! 

## Contact us

Do you have any input or questions about this guide, or the DreamFactory platform? We’d love to hear from you! E-mail us at support@dreamfactory.com with your feedback.
