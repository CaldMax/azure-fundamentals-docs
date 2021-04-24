# Identity, Governance and Compliance

## Authentication VS Authorization
- Authentication establishes the user's identity, but authorization is the process of establishing what level of access an authenticated person or service has

## Azure Active Directory
- Original MS AD was to manage multiple components on premises using a single identity
- Azure AD can be used by
  - IT admin (to control access to applications)
  - App developers (to provide standards like SSO or using existing credentials)
  - Users (to manage their identities)
  - Online subscribers (MS 365, MS Office 365, Azure and so users already use azure AD)
    - A tenant is a representation of an organization. A tenant is typically separated from other tenants and has its own identity
- Provides
  - authetication
  - sso
  - application management
  - device management

## Multifactor authetication
- Something the user knows
- Something the user has
- Something the user is
- Azure AD free enables multifacotr via app, phone call or SMS
- Azure AD premium (P1/P2) allow comprehensive configuration and conditional access policies

## Condition Access
- tool to allow Azure AD to allow or deny access to resources based on identity signals (who is, where is, what uses)