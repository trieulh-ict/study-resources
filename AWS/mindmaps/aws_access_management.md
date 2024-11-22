
# AWS Identity and Access Management (IAM)

## Overview
- **Identity Management**
  - Create and manage users, groups, and roles
  - Central control over access to AWS resources
- **Access Control**
  - Authentication and authorization for resources

## IAM Components
- **Users**
  - Represents individual identities
  - Assigned specific permissions
- **Groups**
  - Collection of users with common permissions
  - Simplifies permission management
- **Roles**
  - Temporary permissions for AWS resources
  - Used by AWS services or external users
- **Policies**
  - JSON-based documents
  - Define permissions and access control rules

## Authentication
- **Password Policies**
  - Set complexity requirements for user passwords
- **Multi-Factor Authentication (MFA)**
  - Adds an extra layer of security for user sign-in

## Authorization
- **Managed Policies**
  - AWS-managed or customer-managed policies
  - Reusable across multiple users and roles
- **Inline Policies**
  - Policies directly attached to a user, group, or role
  - Specific to a single entity

## Best Practices
- **Principle of Least Privilege**
  - Grant only permissions necessary for tasks
- **MFA Enforcement**
  - Enable MFA for privileged users
- **Use Roles for Services**
  - Avoid embedding credentials; use IAM roles for applications running on AWS
- **Regular Audits**
  - Review IAM permissions regularly to reduce security risks
