> **Required reading before repository work:** [NATIVE-PUSH-TO-DEPLOY.md](NATIVE-PUSH-TO-DEPLOY.md).
> Current operating instruction: this policy supersedes conflicting runner, CI and deployment guidance below. Retained legacy procedures are not the native execution route. Native Northflank test/staging applications do not require Actions runners; qualify before a deliberate production main push, not again on main. Current slot route: native buildpacks triggered by intended branch pushes, not manual image selection.

# Organization maintenance

Generic, secret-configured organization maintenance automation.

Implementation is tracked in issue #1. No renewal workflow is installed or active yet.
Runtime identities, destinations, credentials and private receipts do not belong in public source or logs.

Scheduled workflows can be delayed or disabled after repository inactivity. A schedule alone does not prove continuing protection or detect its own absence.
