# Permissions for the Retail Mobile App

## Context

When developing a mobile app for a retail company, it is important to determine which permissions to request from users.

## Decision

The app should only ask for permissions that enable access to push notifications and external links to payment gateways of financial institutions.

## Rationale

Requesting only specific permissions that are necessary for the app's functionality is a best practice for protecting user data. As a retail app, it is important to be able to promote products and offers based on the user's history. Additionally, redirecting payments to trusted financial institutions can ensure secure transactions.

## Consequences

It is important to continually monitor and evaluate push notifications to ensure that only relevant and useful notifications are sent to users. This will help prevent user dissatisfaction. Ensuring the stability and security of the mobile app after payment redirection is also crucial for building user trust and confidence.
