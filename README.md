# Design Patterns Documentation

## Project Description

This project explains three common software design patterns:

1. Singleton
2. Factory
3. Observer

The project explains the problem solved by each pattern,
its purpose, and situations where it can be used.

---

# 1. Singleton Pattern

## Problem

Sometimes an application requires only one instance of a particular
object.

Creating multiple instances may be unnecessary.

## Solution

The Singleton pattern ensures that only one instance of a class
is available.

## Example

A configuration manager can use Singleton so that the application
uses one shared configuration object.

## When to Use

Singleton can be used when an application requires one shared
instance throughout its operation.

---

# 2. Factory Pattern

## Problem

An application may need to create different types of related objects.

Creating those objects directly in many places can make the application
more difficult to maintain.

## Solution

The Factory pattern provides a central way to create the required object.

## Example

A notification system may need:

- Email notification
- SMS notification
- Push notification

A Factory can decide which notification object should be created.

## When to Use

Factory can be used when an application needs to create different
types of related objects.

---

# 3. Observer Pattern

## Problem

Sometimes one object changes and several other objects need to know
about that change.

## Solution

The Observer pattern allows multiple objects to receive updates
automatically.

## Example

A YouTube channel can notify multiple subscribers when a new video
is uploaded.

## When to Use

Observer can be used when multiple objects need to receive updates
when another object changes.

---

# Comparison

| Pattern | Main Purpose | Example |
|---|---|---|
| Singleton | One shared instance | Configuration |
| Factory | Object creation | Notifications |
| Observer | Automatic updates | Subscribers |

---

# Conclusion

Design patterns provide reusable approaches to common software
design problems.

This project demonstrates the basic concepts of Singleton,
Factory, and Observer patterns.
## GitHub Workflow Completed

- Repository created
- Design pattern documentation added
- Multiple meaningful commits created
- Feature branch created
- Pull request created
- Feature branch merged
- README documentation maintained

## Author

Akash
