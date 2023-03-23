# DevOps Best Practices

This is a guideline of best practices that we can apply to our software projects. DevOps best practices include subjects such as agile project management, shifting left with CI/CD, automation, monitoring, observability, continuous feedback, and others. These tips are based on books, articles and professional experience.

# Table of Contents
1. Identify tests that can be automated
2. Run the tests in parallel

## Identify tests that can be automated

It is unlikely that 100% of the tests can be automated since there would at least be some tests where manual testing would be more effective when compared to automation tests. Since test automation is core to CI/CD pipeline, realizing those test cases which can be automated is a crucial best practice for CI/CD. We can automate tests that are executed on a frequent basis and tests that require knowledge and depend on a specific set of testers.
