Many organizations use Microsoft Active Directory to control a user’s ability to login to various environments and as a way to provide RBAC (role-based access controls) through Groups.

OCP works with many authentication providers such as Github, Gitlab, HTPASSWD, Google, OpenID, as well as LDAP. Active Directory is based on LDAP so it will be used to allow users to login to the OCP cluster.

In this demonstration, I will describe the users and groups that are setup in Active Directory and the roles that each of these users will have in my demo environment. Secondly, I will walk you through the information gathering that you will need to do to define the OU (Organizational Unit) structure and LDAP settings. Next, I will show a quick example on how to troubleshoot issues with logging into OCP using the Active Directory/LDAP provider. Lastly, you will see how group membership can be used to provide role-bindings to allow users to have various levels of access to the cluster and to specific projects/namespaces.

https://www.myopenshiftblog.com/adding-active-directory-oauth-provider/
