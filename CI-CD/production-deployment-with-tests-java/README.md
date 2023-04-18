<!-- Copyright Yahoo. Licensed under the terms of the Apache 2.0 license. See LICENSE in the project root. -->

![Vespa Cloud logo](https://cloud.vespa.ai/assets/logos/vespa-cloud-logo-full-black.png)

# Vespa Cloud sample applications - Production Deployment with Java Tests

A minimal Vespa Cloud application for deployment into a Production zone - with basic Java-tests

See [Vespa Cloud Automated Deployments](https://cloud.vespa.ai/en/automated-deployments) for details.

Test using:

    mvn test -D test.categories=system -D vespa.test.config=ext/test-config.json 
    mvn test -D test.categories=staging-setup -D vespa.test.config=ext/test-config.json
    mvn test -D test.categories=staging -D vespa.test.config=ext/test-config.json 
