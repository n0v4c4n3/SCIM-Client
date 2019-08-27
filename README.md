SCIM-Client
===========

ANII branch of SCIM client with UMA authorization.
SCIM is a specification designed to reduce the complexity of user management operations by providing a common user schema
and the patterns for exchanging this schema using HTTP in a platform-neutral fashion. The aim of SCIM is achieving
interoperability, security, and scalability in the context of identity management.

Developers can think of SCIM merely as a REST API with endpoints exposing CRUD functionality (create, update, retrieve and delete).

This project consists of a ready-to-use Java client to interact with those endpoints.

Detailed specifications for SCIM can be found at [RFC 7642](https://tools.ietf.org/html/rfc7642),
[RFC 7643](https://tools.ietf.org/html/rfc7643), and [RFC 7644](https://tools.ietf.org/html/rfc7644). 

### How to run tests
* Import keys provided to profile
* ... and run maven. Examples:
   - `mvn test`
   - `mvn -Dcfg=<profile-name> test`
   - `mvn -Dtestmode=true test`
