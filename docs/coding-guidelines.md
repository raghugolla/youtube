Hey Reviewer, please take care of the following things in this PR:

No Pull request is to be approved till it doesn't have a Tech Spec, a Test Plan and a Post Release Monitoring Plan.

Enforce the changes requested by the SonarQube in that code which was modified or added in the pull request.

Name of the variable, function, method, class or package should tell the intent.Read more

Type hints are a must for the function/method parameters and return value.Read more

Functions, methods and classes should be small and focused on one thing. Functions/Methods for an operation and classes for a concept respectively.Read more

If explaining the working of a block of code requires comments, then that code is a candidate for refactoring.Read more  

Any new code must be covered with Unit Tests to guard it.Read more  

In a class, only entry-point methods should be public. Rest all should be private. Methods that are to be overridden by the subclasses should be set as protected.Read more

Superclass should always be abstract. It should not happen that a superclass and a subclass are being utilized as variants of each other. Read more

The PR should ideally be kept small, with a minimum of 300 lines. If the changes exceed 300 lines, it is recommended to create a feature branch and submit separate pull requests for each logical chunk of the changes against the feature branch.
