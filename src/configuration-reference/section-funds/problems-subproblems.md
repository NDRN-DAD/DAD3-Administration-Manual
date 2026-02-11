[Home](../../index.md) / [Configuration Reference](../index.md) / [Section: Funds](index.md) / Problems / Subproblems

# Problems / Subproblems

**Page Type:** Table (URL: [https://dad3.ndrn.org/admin/admindisplayadvproblemsubproblems](https://dad3.ndrn.org/admin/admindisplayadvproblemsubproblems)) <!--style: Subtitle -->

_Has Field Mapping_ / **Associated Record Types:** [Funding Sources](funding-sources.md), [Local Data Fields](../section-local-data/local-data-fields.md) (Local Data)

**Problems** are used in conjunction with **Subproblems** to categorize both cases and projects, for federal reporting purposes.

Problems are not associated directly with Funding Sources. They are associated with one or more Subproblems, and each Problem/Subproblem pair is then associated with Funding Sources. This settings page defines the Funding Source associations, as well as any custom Local Data field associations.

![Problems / Subproblems admin page screenshot](../../images/Funds-Problems%20%26%20Subproblems.png)

## Problems & Subproblems Form

### Basic Info Tab

This tab defines the Associated Problem / Subproblem pair. 

![Screenshot of Funds Problems & Subproblems Form Basic Info tab](../../images/Funds-Problems%20&%20Subproblems-Form-Basic%20Info.png)

### Funds Tab

Under some funding sources (e.g. PAIR, CAP), subproblems are not reported. In those cases, the Problem is associated with a single Subproblem for that Funding Source (usually with the same label as the Problem, though agency setups vary).

When a Problem has *multiple* Suproblem selections for a Funding Source, the Problem should be associated with the default Subproblem (e.g. Not Selected), and that "Problem/Not Selected" pair should then be associated with that Funding Source. This allows the service request Subproblem dropdown selection to function correctly.

![Screenshot of Funds Problems & Subproblems Form Funds tab](../../images/Funds-Problems%20&%20Subproblems-Form-Funds.png)

### Local Data Fields Tab

```admonish important
Do not select any Local Data Fields in this section. In most cases, nothing should be checked on this tab. Any customization to Local Data Fields should be done on the [Local Data Fields](../section-local-data/local-data-fields.md) page.
```

![Screenshot of Funds Problems & Subproblems Form Local Data Fields tab](../../images/Funds-Problems%20&%20Subproblems-Form-Local%20Data%20Fields.png)

[← Previous: Subproblems](subproblems.md) | [Next: Races →](races.md)
