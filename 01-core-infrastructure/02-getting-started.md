# Getting started with Google Cloud Platform

## The Google Cloud Platform Resource Hierarchy

1. Choose the correct completion: Services and APIs are enabled on a per-__________ basis.

- [X] Project
- [ ] Folder
- [ ] Organization
- [ ] Billing account

2. True or false: Google manages every aspect of Google Cloud Platform customers' security.

- [ ] True
- [X] False

3. Your company has two GCP projects, and you want them to share policies. What is the less error-prone way to set this up?

- [ ] Duplicate all the policies on one project onto the other
- [X] Place both projects into a folder,and define policies on the folder

## Resources and IAM

1. When would you choose to have an organization node? (Choose all that are correct. Choose 2 responses.)

- [X] When you want to create folders
- [ ] When you want to organize resources into proyects
- [X] When you want to apply organization-wide policies centrally
- [ ] Theres is no choice; organization nodes are mandatory

2. Order these IAM role types from broadest to finest-grained.

- [X] Primitive roles, predefined roles, custom roles
- [ ] Custom roles, predefined roles, primitive roles
- [ ] Predefined roles, custom roles, primitive roles

3. Can IAM policies that are implemented higher in the resource hierarchy take away access that is granted by lower-level policies?

- [ ] Yes
- [X] No

## Getting started with Google Cloud Platform

1. True or False: In Google Cloud IAM: if a policy applied at the project level gives you Owner permissions, your access to an individual resource in that project might be restricted to View permission if someone applies a more restrictive policy directly to that resource.

- [ ] True
- [X] False

2. True or False: All Google Cloud Platform resources are associated with a project.

- [X] True
- [ ] False

3. Service accounts are used to provide which of the following? (Choose all that are correct. Choose 3 responses.)

- [X] A way to restrict the actions a resource (such as a VM) can perform
- [X] A way to allow users to act with service account permissions
- [X] Authentication between Google Cloud Platform services
- [ ] A set of predefined permissions

4. How do GCP customers and Google Cloud Platform divide responsibility for security?

- [X] Google takes care of the lower parts of the stack and customers are responsible for the higher parts
- [ ] All aspects of security are Google's responsibility
- [ ] All aspects of security are the customer's responsibility
- [ ] Google takes care of the higher parts of the stack, and customers are responsible for the lower parts

5. Which of these values is globally unique, permanent, and unchangeable, but chosen by the customer?

- [ ] The project's billing and credit-car number
- [ ] The project name
- [ ] The project number
- [X] The project ID

6. Consider a single hierarchy of GCP resources. Which of these situations is possible? (Choose all that are correct. Choose 3 responses.)

- [X] There is an organization node, and there is at least one folder
- [X] There is no organization node, and there are no folders
- [X] There is an organization node, and there are no folders
- [ ] There is no organization node, but theres is at least one folder
- [ ] There are two or more organization nodes

7. What is the difference between IAM primitive roles and IAM predefined roles?

- [ ] Primitive roles can only be granted to single users. Predefined roles can be associated with a group
- [ ] Primitive roles are changeable once assigned. Predefined roles can never be changed
- [X] Primitive roles affect all resources in a GCP project. Predefined roles apply to a particular service in a project
- [ ] Primitive roles only allow viewing, creating, and deleting resources. Predefined roles allow any modification
- [ ] Primitive roles only apply to the owner of the GCP project. Predefined roles can be associated with any user

8. Which statement is true about billing for solutions deployed using Cloud Marketplace (formerly known as Cloud Launcher)?

- [X] You pay only for the underlying GCP resources you use, with the possible addition of extre fees for commercially licensed software
- [ ] You pay only for the underlying GCP resources that you use; Google pays the license fees for commercially licensed software
- [ ] Cloud Marketplace solutions are always free
- [ ] After a trial period, each Cloud Marketplace solution assesses a fixed recurring monthly fee
