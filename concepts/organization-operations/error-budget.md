# Error Budget

An error budget is the maximum amount of time that a technical system can fail without contractual consequences.

For example, if your [[service-level-agreement]] (SLA) specifies that systems will function 99.99% of the time before the business has to compensate customers for the outage, that means your error budget (or the time your systems can go down without consequences) is 52 minutes and 35 seconds per year.

If your SLA promises 99.95% uptime, your error budget is four hours, 22 minutes, and 48 seconds. And with an SLA promise of 99.9% uptime, your error budget is eight hours, 46 minutes, and 12 seconds.

## Why do tech teams need error budgets?

The development team can ‘spend’ this error budget in any way they like. If the product is currently running flawlessly, with few or no errors, they can launch whatever they want, whenever they want. Conversely, if they have met or exceeded the error budget and are operating at or below the defined SLA, all launches are frozen until they reduce the number of errors to a level that allows the launch to proceed.

## Useful links
- [What is an error budget—and why does it matter?](https://www.atlassian.com/incident-management/kpis/error-budget)
- [How maintenance windows affect your error budget—SRE tips
](https://cloud.google.com/blog/products/management-tools/sre-error-budgets-and-maintenance-windows)

[//begin]: # "Autogenerated link references for markdown compatibility"
[service-level-agreement]: service-level-agreement "Service Level Agreement"
[//end]: # "Autogenerated link references"
