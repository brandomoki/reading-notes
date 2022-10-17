# Access Control (ACL)

## [5 steps to RBAC](https://www.csoonline.com/article/3060780/5-steps-to-simple-role-based-access-control.html)

- What is Role Based Access Control (RBAC) and why do we care?

  - assigning system access to users based on their role within an organization

- Describe a Role/Permission hierarchy that you might implement using RBAC.

  - In the case of Verizon a tech support person may only have basic access to the types of data plans and support services but no access to personal information or billing

- What approach might you take to implement RBAC?

  - inventory my systems and assign roles based on employee job title. Never make one off changes for circumstances and do audits often  

## [wiki - RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)

- If Authentication is “you are who you say you are,” what is Authorization?

  - Authorization is the permission to be able to access only what they are authorized to access

- Name three primary rules defined for RBAC.

  - Role assignment: A subject can exercise a permission only if the subject has selected or been assigned a role.
  - Role authorization: A subject's active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized.
  - Permission authorization: A subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.

- Describe RBAC to a non-technical friend.

  - RBAC is as simple as giving permission to those who's job requires the access and nothing else

## [RBAC tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA)

- What Are access rights Associated with? The User? or The Role? Explain.

  - access rights are associated to the role and not the user.

- Access Rights, or Authorization, is activated after a user successfully does what?

  - After the user is assigned a role

- Explain how RBAC might benefit a business.

  - This keeps data confidential and allows the business to see what role and or user accessed what. Roles are ready to be assigned and have base access according to the role
