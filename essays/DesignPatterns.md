---
layout: essay
type: essay
title: "Usage of Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2023-11-29
published: true
labels:
  - Software Engineering
  - Design Patterns
---

# <img width="50%" class="rounded float-start pe-4" src="../img/designpatterns.png">

## What are Design Patterns
Design patterns are reusable solutions to common problems that arise in software design. In addition to offering a flexible and effective way to organize code, they serve as a representation of best practices. Instead of being limited to a single issue or field, design patterns are applicable in a variety of contexts.

## Application
Design patterns are a vital tool in software development and was used in the Subscription and Publication design pattern from the Meteor framework. While the 
Subscription design pattern enables subscribers to concentrate on various facets of the published material, each receiving customized updates depending on their subscriptions, the Publication design pattern distributes information. The foundation of Meteor's real-time data transmission is this design pattern, which permits modules to stay dynamically linked and guarantees that changes in one area spread to interested parties without the need for explicit polling or manual intervention. For developers and consumers alike, the Subscription and Publication design pattern fosters a cooperative and adaptable environment that facilitates communication and data sharing inside the software domain.

The Singleton design pattern is a critical principle in software architecture, similar to a castle guardian. It ensures that only one instance of a given class exists, allowing controlled access to the class's unique resources. This pattern resembles the role of a castle guardian in that it supervises the creation of a single, globally accessible instance of a class. Singleton instances provide access to critical services or resources within an application, such as managing system configurations, controlling access to a shared database connection, or orchestrating logging features. However, Singleton has some drawbacks, including tight coupling, limited flexibility, and poor testability. When used wisely, Singleton acts as a steadfast protector, ensuring the controlled and efficient use of critical resources within the software architecture.

## Conclusion
To conclude, design patterns in software engineering are reusable solutions that demonstrate structured problem-solving approaches that balance usability and efficiency, such as the Publish Subscribe pattern in Meteor for real-time 
communication and the Singleton pattern for ensuring a single instance for critical resources. Nonetheless, there are numerous other design patterns that can be used to help us become better developers.
