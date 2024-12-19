# ADR-0003: User Accounts

## Status

Accepted

## Context

User should be able to be authenticated (see [ADR-0002](0002-authentication-and-authorization.md)).

## Decision

User accounts will be stored in a database.
// more details

## Consequences

Users can use the credentials stored in the database to authenticate themselves to use the application.
// security implications
// - we need to harden the application ourselves
// - brute force attacks
// account management implications
// - password recovery
// - account creation
