## Create a New Tenant

**1. Create a new Tenant named POC Role in Azure. This will ensure that you don't interfere with the production tenant the organization is already using.**

https://learn.microsoft.com/en-us/azure/active-directory/fundamentals/create-new-tenant

Q: what is a tenant in azure ?
ANS:

**2. Add Users to the New Tenant**

https://learn.microsoft.com/en-us/azure/active-directory/fundamentals/add-users#add-a-new-user

**3. Create a Group in the New Tenant**
Create a group in the new tenant you created. The group should be named "Developers".

https://learn.microsoft.com/en-us/azure/active-directory/roles/groups-create-eligible?tabs=ms-powershell#azure-portal

**4. Assign Users to Group**
Assign the users in the new tenant to the new Developers group.

https://learn.microsoft.com/en-us/azure/active-directory/fundamentals/how-to-manage-groups#add-members-or-owners-of-a-group

**5. Enable Security Defaults**
Make sure Security Defaults are enabled in the tenant, which forces MFA for log-ins.

https://learn.microsoft.com/en-us/azure/active-directory/fundamentals/security-defaults

**6. Clean Up Resources**
Delete all the resources created during this proof-of-concept to save costs.

[https://learn.microsoft.com/en-us/azure/active-directory/enterprise-users/directory-delete-howto](https://learn.microsoft.com/en-us/azure/active-directory/enterprise-users/directory-delete-howto)
