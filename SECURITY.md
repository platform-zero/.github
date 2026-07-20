# Security Policy

Report suspected vulnerabilities privately through GitHub's **Report a vulnerability**
feature on the affected repository. Do not open a public issue containing secrets,
credentials, exploit details, or private infrastructure information.

The currently deployed release and the default branch of each active module are
supported. Security fixes are validated through module CI and the controlled
deploy, full-test, and rollback release gate.

Confirmed credentials are revoked before repository remediation. Proven test
fixtures may be allowlisted only by rule and path with an explanatory comment.
