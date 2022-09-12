# Pull Request Git Commit Checker
A minor action which checks commits on a pull request for certain conformity
policies. If all commits pass, the action succeeds and no comment emitted. If a
check fails for one or many commits, the action fails and a comment is placed on
the PR explaining which commits caused the failure and why. For instance, if
contributed commits need to be signed off, a comment with this message will
appear:

`e3042c1`**: foobar**
* *check_signed_off: does not contain a valid Signed-off-by line*


*Uses [SemVer 2.0.0](https://semver.org/spec/v2.0.0.html)*
