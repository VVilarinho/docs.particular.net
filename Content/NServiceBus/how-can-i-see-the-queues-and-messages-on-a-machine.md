---
title: How to See the Queues and Messages on a Machine?
summary: See queues on local machine using Server Explorer in Visual Studio, The most interesting property is BodyStream.
originalUrl: http://www.particular.net/articles/how-can-i-see-the-queues-and-messages-on-a-machine
tags: []
---

You can see all the queues on the local machine using Server Explorer in Visual Studio:

![Server Explorer](ServerExplorer.jpg "Server Explorer")

If there is a message in one of the queues, select it and view the properties of the message in the property panel in Visual Studio
(usually on the bottom right):

![Visual Studio properties](VisualStudioProperties.jpg "Visual Studio properties")

The most interesting property is the BodyStream as it allows you to see the contents of the message:

![Message contents](BodyStream.jpg "Message contents")


