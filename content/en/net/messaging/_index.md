---
type: docs
title: "Messaging module"
gitUrl: "https://github.com/pip-services3-dotnet/pip-services3-messaging-dotnet"
no_list: true
weight: 90
description: > 
    Asynchronous Messaging for Pip.Services in .NET.  

    This module is a part of the [Pip.Services](http://pipservices.org) polyglot microservices toolkit.
    It contains a set of interfaces and classes for working with message queues, as well as an in-memory message queue implementation. 
---

### Modules

The module contains the following packages:

- [**Build**](build) - in-memory message queue factory
- [**Queues**](queues) - contains interfaces for working with message queues, subscriptions for receiving messages from the queue, and an in-memory message queue implementation.
- [**Connect**](connect) - contains an interface used to create message queue connections
- [**Test**](test) - contains a class used to test message reception

### Use

Install the dotnet package as
```bash
dotnet add package PipServices3.Messaging
```

TODO: add example
