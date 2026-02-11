[Home](../../index.md) / [Configuration Reference](../index.md) / [Section: Users](index.md) / Security Groups

# Security Groups

**Page Type:** Table (URL: [https://dad3.ndrn.org/admin/admindisplaysecuritygroups](https://dad3.ndrn.org/admin/admindisplaysecuritygroups)) <!--style: Subtitle -->

**Associated Record Type:** [Users](index.md)

**See [Appendix A: Permissions Reference](../../appendix/permissions.md) for a complete list of DAD permissions.**

Security groups are used to manage user access by grouping permissions together. Each security group is configured with a specific set of permissions that define what actions members of that group are allowed to perform. Instead of assigning permissions individually to each user, administrators add users to one or more security groups, and the users automatically inherit the permissions associated with those groups.

```admonish info
**Permissions are additive**, meaning a user’s effective access is the combined total of all permissions granted by every security group they belong to. If a user is a member of multiple security groups, they receive all permissions from each group—nothing is overridden or taken away by belonging to another group. 

For example, if one group allows viewing records and another allows editing data, a user who belongs to both groups can *both* view records *and* edit data.
```

One Security Group should be mapped to **Administrators**, and one Security Group should be mapped to **All Users**. All other Security Groups should be mapped to the **General** Mapped Security Group.

```admonish important
For DAD to function correctly, **ALL** users must be be added to the **All Users** Security Group.
```

![Security Groups admin page screenshot](../../images/Users-Security%20Groups.png)

## Security Groups Form

### Basic Info Tab

Enter the name, description and mapping of the Security Group.
![Screenshot of Users Security Groups Form Basic Info tab](../../images/Users-Security%20Groups-Form-Basic%20Info.png)

### Users Tab

Select the users in this Security Group.
![Screenshot of Users Security Groups Form Users tab](../../images/Users-Security%20Groups-Form-Users.png)

### Permissions Tab

Select the permissions to grant users in this Security Group.

**See [Appendix A: Permissions Reference](../../appendix/permissions.md) for a complete list of DAD permissions.**

![Screenshot of Users Security Groups Form Permissions tab](../../images/Users-Security%20Groups-Form-Permissions.png)

[← Previous: User Maintenance](user-maintenance.md) | [Next: User Assignment Types →](user-assignment-types.md)
