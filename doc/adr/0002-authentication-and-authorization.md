# ADR-0002: Authentication and Authorization

## Status

Accepted

## Context

The application will be available to the public.
There are different types of users with different permissions.

// more information about the context:
// what are the users?
// what are the permissions?
// Are there existing authentication solutions, for example OAuth or Identity managemement systems?

## Decision

To allow users to only be able to interact with the application according to their permissions, we need to authenticate users.

The implementation decision for the authentication can be found in [ADR-0003: User Accounts](0003-user-accounts.md).

## Consequences

Users can only interact with the application according to their permissions.

// provide positive and negative consequences of the decision
