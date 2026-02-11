[Home](../../index.md) / [Configuration Reference](../index.md) / [Section: Contacts](index.md) / Contact Types

# Contact Types

**Page Type:** Table (URL: [https://dad3.ndrn.org/admin/admindisplayadvcontacttypes](https://dad3.ndrn.org/admin/admindisplayadvcontacttypes)) <!--style: Subtitle -->

**Contact Types** define several categories of contacts (individuals or organizations) that may be tracked for Clients, Service Requests or Projects. By default, the following Contact Types exist:

* Adversary - the adversary or opposing party for a service request or case
* Caller - the individual calling the P&A for assistance (used in DAD 2.0 in creation of Quick I&Rs)
* Guardian - the legal guardian for a client
* Primary Contact - the primary contact for a client
* Referrer - the organization or individual who referred the caller or client to the P&A/CAP
* General Contact - a catch all catgeory for all other contacts

Agencies can create additional Contact Types if desired. Each Contact Type can be associated with Clients, Service Requests, and/or Projects. Agency configurations and conventions used vary, but a typical configuration could be as follows:

| Contact Type | Associated Record Types |
|---|---|
| Adversary | Service Request, Project |
| Caller | Service Request |
| Guardian | Client |
| Primary Contact | Client |
| Referrer | Service Request |
| General Contact | Client, Service Request, Project |

```admonish note
The Display Order settings for Contact Types are no longer in use.
```

![Contact Types admin page screenshot](../../images/Contacts-Contact%20Types.png)

## Contact Types Form

Options: Is the Default Option, Associated with Clients, Client Display Order, Associated with SRs, SR Display Order, Associated with Projects, Project Display Order

![Screenshot of Contacts Contact Types Form](../../images/Contacts-Contact%20Types-Form.png)

[← Previous: Section: Contacts](index.md) | [Next: Guardian Types →](guardian-types.md)
