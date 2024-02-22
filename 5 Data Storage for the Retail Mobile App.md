# Data Storage for the Retail Mobile App

## Context

The team needs to decide on the most suitable data storage strategy for the mobile app, with an emphasis on offline functionality and synchronization.

## Decision

After thorough analysis, the team recommends using SQLite for local storage on the device and Redis for the cloud-based database.

## Rationale

SQLite is an efficient option for local storage, which supports offline functionality. On the other hand, Redis provides a scalable solution for cloud-based database needs. This approach aligns with the project's requirements for seamless synchronization.

## Consequences

Implementing a dual storage approach requires careful synchronization logic. However, it ensures optimal performance and meets the project's requirement of supporting offline mode effectively.
