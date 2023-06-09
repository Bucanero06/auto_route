Contributing to the AutoRoute Project
=====================================

Introduction
------------

Thank you for your interest in contributing to the AutoRoute project!
Our goal is to simplify and automate the creation of SaaS/PaaS
solutions. We’re excited to welcome you to our community.

Here’s a guide on how you can contribute:

Getting Started
---------------

**Understanding the Project:** Familiarize yourself with the project’s
features, design philosophy, and architecture. Spend some time exploring
the codebase and reading the existing documentation (md and docstrings).

-  `Components_Breakdown.md <Components_Breakdown.md>`__
-  `Proposal.md <Proposal.md>`__
-  `Part 1 - Creating FastAPI Application and Auto-generating Class
   Method
   Endpoints.md <1%20-%20Creating%20FastAPI%20Application%20and%20Auto-generating%20Class%20Method%20Endpoints.md>`__
-  `Part 2 - Generating OpenAPI Specification and Interactive
   Documentation for
   FastAPI.md <2%20-%20Generating%20OpenAPI%20Specification%20and%20Interactive%20Documentation%20for%20FastAPI.md>`__
-  `Part 3 - Exploring the Generated Python Client Library and
   Customizing Its
   Configuration.md <3%20-%20Exploring%20the%20Generated%20Python%20Client%20Library%20and%20Customizing%20Its%20Configuration.md>`__
-  `Part 4 - FastAPI Application and Generated Client Library: Complete
   Guide for
   Beginners.md <4%20-%20FastAPI%20Application%20and%20Generated%20Client%20Library%3A%20Complete%20Guide%20for%20Beginners.md>`__
-  `Dockerfile_example.md <Dockerfile_example.md>`__
-  `how_to_improve_microservice.md <how_to_improve_microservice.md>`__

**Quick Guide:**

::

   @auto_route
   def get_customer_id():
       return "customer_id"

1.  *@auto_route:*

    1. The **naming conversion** for functions using this wrapper is
       ``http-method_tag_*detail`` :

       1. *where* http_method is in
          ``[get, post, put, delete, patch, options, head, trace]``
       2. the **tag** is the name of the class that the function is in,
          e.g. ``customer``
       3. the **detail** is the name of the function, in the example
          above, the detail would be ``id``
       4. e.g.  ## Areas of Contribution

2.  **Documentation:** Clear, comprehensive documentation is crucial for
    any successful open-source project. Help us improve our
    documentation by creating tutorials, adding usage examples, and
    improving descriptions of features and configurations.

3.  **Continuous Integration/Continuous Deployment (CI/CD):** We’re
    always aiming to improve our automated testing and deployment
    processes. If you have experience with CI/CD platforms like GitHub
    Actions, Travis CI, or Jenkins, your expertise could be incredibly
    valuable.

4.  **Automated Testing:** Robust testing is a core part of our
    commitment to code quality. Help us achieve this by writing unit
    tests and improving our code coverage.

5.  **Code Quality Checks:** We’re committed to maintaining a clean and
    readable codebase. Contribute by improving our linting processes,
    static code analysis, and enforcing our code style guidelines.

6.  **Debugging AI Models:** This is an exciting part of our project. If
    you have ideas on how to include more common issues and security
    checks, or ways to extend our debugging with user-defined checks, we
    would love to hear from you.

7.  **Payment Integrations:** We currently support Stripe, but we aim to
    provide more flexibility for our users. Help us integrate other
    payment providers like PayPal, Square, or even cryptocurrencies.

8.  **Configuration Options:** We want to make our project as flexible
    as possible. Your contributions could help us support different
    deployment options, database backends, and more.

9.  **API Wrappers:** We currently provide wrappers for Google
    applications. Help us extend our reach by adding wrappers for other
    popular APIs, such as social media APIs or other cloud service APIs.

10. **Multi-Language Support:** We already support over 50 languages
    thanks to openapi.json and the OpenAPI SDK generator. Help us extend
    our reach by translating our documentation or other parts of our
    project into other languages.

Community
---------

Finally, we encourage all contributors to participate in our community.
Join our forum or chat room, sign up for our mailing list, and help us
build a friendly, active community around our project.

Thank you for considering contributing to AutoRoute. We look forward to
working with you!
