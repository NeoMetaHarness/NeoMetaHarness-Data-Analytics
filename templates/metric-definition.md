# Metric definition — extension enable success

## Definition
Successful extension enables divided by completed enable attempts within the same release and observation window.

## Events
Use extension.lifecycle.completed with action=enable. Include both successes and failures in the denominator.

## Reporting
Report numerator, denominator, window, build version and opt-in coverage. Show insufficient sample as unavailable instead of 100%. Never infer absent data from users who did not opt in.

## Validation
Reconcile event counts against isolated local test runs and document any dropped events.
