# ADR-0001: TeachingPerson Interface

## Status

Accepted

## Context

Relevant User Stories:
- [milestone/1]()
- [issues/1]()
- [issues/6]()
- [issues/8]()

At a university there are different types of teaching person. These all have different properties.
For example there are professors, guest professors, lecturers and teacher for special tasks.


## Decision

To allow future extensions, we create an interface for teaching persons.
The TeachingPerson interface specifies the minimal requirements a teaching person must implement.

Specifically, the teaching person must be able to:

- List all courses taught by a teaching person.
- Create a course.
- Create an exam.

## Consequences

The TeachingPerson interface provides a standard way to introduce new types of teaching persons to the application.

// provide positive and negative consequences of the decision
