---
title: Getting started with GitHub Enterprise Cloud
intro: 'Get started with setting up and managing your {% data variables.product.prodname_ghe_cloud %} organization or enterprise account.'
versions:
  fpt: '*'
  ghec: '*'
---

This guide will walk you through setting up, configuring and managing your {% data variables.product.prodname_ghe_cloud %} account as an organization or enterprise owner.

{% data reusables.enterprise.ghec-cta-button %}

## Part 1: Choosing your account type

{% data variables.product.prodname_dotcom %} provides two types of Enterprise products:

- **{% data variables.product.prodname_ghe_cloud %}**
- **{% data variables.product.prodname_ghe_server %}**

The main difference between the products is that {% data variables.product.prodname_ghe_cloud %} is hosted by {% data variables.product.prodname_dotcom %}, while {% data variables.product.prodname_ghe_server %} is self-hosted.

For more information about {% data variables.product.prodname_ghe_cloud %}, see "[About {% data variables.product.prodname_ghe_cloud %}](/enterprise-cloud@latest/admin/overview/about-github-enterprise-cloud)."

With {% data variables.product.prodname_ghe_cloud %}, you have the option of using {% data variables.product.prodname_emus %}. {% data reusables.enterprise-accounts.emu-short-summary %}

If you choose to let your members create and manage their own personal accounts instead, there are two types of accounts you can use with {% data variables.product.prodname_ghe_cloud %}:

- A single organization account
- An enterprise account that contains multiple organizations

### 1. Understanding the differences between an organization account and enterprise account

Both organization and enterprise accounts are available with {% data variables.product.prodname_ghe_cloud %}. An organization is a shared account where groups of people can collaborate across many projects at once, and owners and administrators can manage access to data and projects. An enterprise account enables collaboration between multiple organizations, and allows owners to centrally manage policy, billing and security for these organizations. For more information on the differences, see "[Organizations and enterprise accounts](/organizations/collaborating-with-groups-in-organizations/about-organizations#organizations-and-enterprise-accounts)."

If you choose an enterprise account, keep in mind that some policies can be set only at an organization level, while others can be enforced for all organizations in an enterprise.

Once you choose the account type you would like, you can proceed to setting up your account. In each of the sections in this guide, proceed to either the single organization or enterprise account section based on your account type.

## Part 2: Setting up your account
To get started with {% data variables.product.prodname_ghe_cloud %}, you will want to create your organization or enterprise account and set up and view billing settings, subscriptions and usage.
### Setting up a single organization account with {% data variables.product.prodname_ghe_cloud %}

#### 1. About organizations
Organizations are shared accounts where groups of people can collaborate across many projects at once. With {% data variables.product.prodname_ghe_cloud %}, owners and administrators can manage their organization with sophisticated user authentication and management, as well as escalated support and security options. For more information, see "[About organizations](/organizations/collaborating-with-groups-in-organizations/about-organizations)."
#### 2. Creating or upgrading an organization account

To use an organization account with {% data variables.product.prodname_ghe_cloud %}, you will first need to create an organization. When prompted to choose a plan, select "Enterprise". For more information, see "[Creating a new organization from scratch](/organizations/collaborating-with-groups-in-organizations/creating-a-new-organization-from-scratch)."

Alternatively, if you have an existing organization account that you would like to upgrade, follow the steps in "[Upgrading your {% data variables.product.prodname_dotcom %} subscription](/billing/managing-billing-for-your-github-account/upgrading-your-github-subscription#upgrading-your-organizations-subscription)."
#### 3. Setting up and managing billing

When you choose to use an organization account with {% data variables.product.prodname_ghe_cloud %}, you'll first have access to a [30-day trial](/get-started/signing-up-for-github/setting-up-a-trial-of-github-enterprise-cloud). If you don't purchase {% data variables.product.prodname_enterprise %} or {% data variables.product.prodname_team %} before your trial ends, your organization will be downgraded to {% data variables.product.prodname_free_user %} and lose access to any advanced tooling and features that are only included with paid products. For more information, see "[Finishing your trial](/get-started/signing-up-for-github/setting-up-a-trial-of-github-enterprise-cloud#finishing-your-trial)."

Your organization's billing settings page allows you to manage settings like your payment method and billing cycle, view information about your subscription, and upgrade your storage and {% data variables.product.prodname_actions %} minutes. For more information on managing your billing settings, see "[Managing your {% data variables.product.prodname_dotcom %} billing settings](/billing/managing-your-github-billing-settings)."

Only organization members with the *owner* or *billing manager* role can access or change billing settings for your organization. A billing manager is a user who manages the billing settings for your organization and does not use a paid license in your organization's subscription. For more information on adding a billing manager to your organization, see "[Adding a billing manager to your organization](/organizations/managing-peoples-access-to-your-organization-with-roles/adding-a-billing-manager-to-your-organization)."

### Setting up an enterprise account with {% data variables.product.prodname_ghe_cloud %}

#### 1. About enterprise accounts

An enterprise account allows you to centrally manage policy and settings for multiple {% data variables.product.prodname_dotcom %} organizations, including member access, billing and usage and security. For more information, see "[About enterprise accounts](/enterprise-cloud@latest/admin/overview/about-enterprise-accounts)."

#### 2. Creating an enterprise account

 {% data variables.product.prodname_ghe_cloud %} customers paying by invoice can create an enterprise account directly through {% data variables.product.prodname_dotcom %}. For more information, see "[Creating an enterprise account](/enterprise-cloud@latest/admin/overview/creating-an-enterprise-account)." 
 
 {% data variables.product.prodname_ghe_cloud %} customers not currently paying by invoice can contact [{% data variables.product.prodname_dotcom %}'s Sales team](https://enterprise.github.com/contact) to create an enterprise account for you.

#### 3. Adding organizations to your enterprise account

You can create new organizations to manage within your enterprise account. For more information, see "[Adding organizations to your enterprise](/enterprise-cloud@latest/admin/user-management/managing-organizations-in-your-enterprise/adding-organizations-to-your-enterprise)."

Contact your {% data variables.product.prodname_dotcom %} sales account representative if you want to transfer an existing organization to your enterprise account.
#### 4. Viewing the subscription and usage for your enterprise account
You can view your current subscription, license usage, invoices, payment history, and other billing information for your enterprise account at any time. Both enterprise owners and billing managers can access and manage billing settings for enterprise accounts. For more information, see  "[Viewing the subscription and usage for your enterprise account](/enterprise-cloud@latest/billing/managing-billing-for-your-github-account/viewing-the-subscription-and-usage-for-your-enterprise-account)."

## Part 3: Managing your organization or enterprise members and teams with {% data variables.product.prodname_ghe_cloud %}

### Managing members and teams in your organization
You can set permissions and member roles, create and manage teams, and give people access to repositories in your organization. 
#### 1. Managing members of your organization
{% data reusables.getting-started.managing-org-members %}
#### 2. Organization permissions and roles
{% data reusables.getting-started.org-permissions-and-roles %}
#### 3. About and creating teams
{% data reusables.getting-started.about-and-creating-teams %}
#### 4. Managing team settings
{% data reusables.getting-started.managing-team-settings %}
#### 5. Giving people and teams access to repositories, project boards and apps
{% data reusables.getting-started.giving-access-to-repositories-projects-apps %}

### Managing members of an enterprise account
Managing members of an enterprise is separate from managing members or teams in an organization. It is important to note that enterprise owners or administrators cannot access organization-level settings or manage members for organizations in their enterprise unless they are made an organization owner. For more information, see the above section, "[Managing members and teams in your organization](#managing-members-and-teams-in-your-organization)."

If your enterprise uses {% data variables.product.prodname_emus %}, your members are fully managed through your identity provider. Adding members, making changes to their membership, and assigning roles is all managed using your IdP. For more information, see "[About {% data variables.product.prodname_emus %}](/enterprise-cloud@latest/admin/authentication/managing-your-enterprise-users-with-your-identity-provider/about-enterprise-managed-users)."

If your enterprise does not use {% data variables.product.prodname_emus %}, follow the steps below.

#### 1. Assigning roles in an enterprise
By default, everyone in an enterprise is a member of the enterprise. There are also administrative roles, including enterprise owner and billing manager, that have different levels of access to enterprise settings and data. For more information, see "[Roles in an enterprise](/enterprise-cloud@latest/admin/user-management/managing-users-in-your-enterprise/roles-in-an-enterprise)."
#### 2. Inviting people to manage your enterprise
You can invite people to manage your enterprise as enterprise owners or billing managers, as well as remove those who no longer need access. For more information, see "[Inviting people to manage your enterprise](/enterprise-cloud@latest/admin/user-management/managing-users-in-your-enterprise/inviting-people-to-manage-your-enterprise)."

You can also grant enterprise members the ability to manage support tickets in the support portal. For more information, see "[Managing support entitlements for your enterprise](/enterprise-cloud@latest/admin/user-management/managing-users-in-your-enterprise/managing-support-entitlements-for-your-enterprise)."
#### 3. Viewing people in your enterprise
To audit access to enterprise-owned resources or user license usage, you can view every enterprise administrator, enterprise member, and outside collaborator in your enterprise. You can see the organizations that a member belongs to and the specific repositories that an outside collaborator has access to. For more information, see "[Viewing people in your enterprise](/admin/user-management/managing-users-in-your-enterprise/viewing-people-in-your-enterprise)."

## Part 4: Managing security with {% data variables.product.prodname_ghe_cloud %}

* [Managing security for a single organization](#managing-security-for-a-single-organization)
* [Managing security for an {% data variables.enterprise.prodname_emu_enterprise %}](#managing-security-for-an-enterprise-with-managed-users)
* [Managing security for an enterprise account without {% data variables.enterprise.prodname_managed_users %}](#managing-security-for-an-enterprise-account-without-managed-users)

### Managing security for a single organization
You can help keep your organization secure by requiring two-factor authentication, configuring security features, reviewing your organization's audit log and integrations, and enabling SAML single sign-on and team synchronization.
#### 1. Requiring two-factor authentication
{% data reusables.getting-started.requiring-2fa %}
#### 2. Configuring security features for your organization
{% data reusables.getting-started.configuring-security-features %}

#### 3. Reviewing your organization's audit log and integrations
{% data reusables.getting-started.reviewing-org-audit-log-and-integrations %}

#### 4. Enabling and enforcing SAML single sign-on for your organization
If you manage your applications and the identities of your organization members with an identity provider (IdP), you can configure SAML single-sign-on (SSO) to control and secure access to organization resources like repositories, issues and pull requests. When members of your organization access organization resources that use SAML SSO, {% data variables.product.prodname_dotcom %} will redirect them to your IdP to authenticate. For more information, see "[About identity and access management with SAML single sign-on](/organizations/managing-saml-single-sign-on-for-your-organization/about-identity-and-access-management-with-saml-single-sign-on)."

Organization owners can choose to disable, enable but not enforce, or enable and enforce SAML SSO. For more information, see "[Enabling and testing SAML single sign-on for your organization](/organizations/managing-saml-single-sign-on-for-your-organization/enabling-and-testing-saml-single-sign-on-for-your-organization)" and "[Enforcing SAML single sign-on for your organization](/organizations/managing-saml-single-sign-on-for-your-organization/enforcing-saml-single-sign-on-for-your-organization)."
#### 5. Managing team synchronization for your organization
Organization owners can enable team synchronization between your identity provider (IdP) and {% data variables.product.prodname_dotcom %} to allow organization owners and team maintainers to connect teams in your organization with IdP groups. For more information, see "[Managing team synchronization for your organization](/organizations/managing-saml-single-sign-on-for-your-organization/managing-team-synchronization-for-your-organization)."

### Managing security for an {% data variables.enterprise.prodname_emu_enterprise %}

With {% data variables.product.prodname_emus %}, access and identity is managed centrally through your identity provider. Two-factor authentication and other login requirements should be enabled and enforced on your IdP. 

#### 1. Enabling and SAML single sign-on and provisioning in your {% data variables.enterprise.prodname_emu_enterprise %}

In an {% data variables.enterprise.prodname_emu_enterprise %}, all members are provisioned and managed by your identity provider. You must enable SAML SSO and SCIM provisioning before you can start using your enterprise. For more information on configuring SAML SSO and provisioning for an {% data variables.enterprise.prodname_emu_enterprise %}, see "[Configuring SAML single sign-on for Enterprise Managed Users](/enterprise-cloud@latest/admin/authentication/managing-your-enterprise-users-with-your-identity-provider/configuring-saml-single-sign-on-for-enterprise-managed-users)."

#### 2. Managing teams in your {% data variables.enterprise.prodname_emu_enterprise %} with your identity provider

You can connect teams in your organizations to security groups in your identity provider, managing membership of your teams and access to repositories through your IdP. For more information, see "[Managing team memberships with identity provider groups](/enterprise-cloud@latest/admin/authentication/managing-your-enterprise-users-with-your-identity-provider/managing-team-memberships-with-identity-provider-groups)."

#### 3. Managing allowed IP addresses for organizations in your {% data variables.enterprise.prodname_emu_enterprise %}

You can configure an allow list for specific IP addresses to restrict access to assets owned by organizations in your {% data variables.enterprise.prodname_emu_enterprise %}. For more information, see "[Enforcing policies for security settings in your enterprise](/enterprise-cloud@latest/admin/policies/enforcing-policies-for-your-enterprise/enforcing-policies-for-security-settings-in-your-enterprise#managing-allowed-ip-addresses-for-organizations-in-your-enterprise)."

#### 4. Enforcing policies for Advanced Security features in your {% data variables.enterprise.prodname_emu_enterprise %}
{% data reusables.getting-started.enterprise-advanced-security %}

### Managing security for an enterprise account without {% data variables.enterprise.prodname_managed_users %}
To manage security for your enterprise, you can require two-factor authentication, manage allowed IP addresses, enable SAML single sign-on and team synchronization at an enterprise level, and sign up for and enforce GitHub Advanced Security features. 

#### 1. Requiring two-factor authentication and managing allowed IP addresses for organizations in your enterprise account
Enterprise owners can require that organization members, billing managers, and outside collaborators in all organizations owned by an enterprise account use two-factor authentication to secure their personal accounts. Before doing so, we recommend notifying all who have access to organizations in your enterprise. You can also configure an allow list for specific IP addresses to restrict access to assets owned by organizations in your enterprise account. 

For more information on enforcing two-factor authentication and allowed IP address lists, see "[Enforcing policies for security settings in your enterprise](/enterprise-cloud@latest/admin/policies/enforcing-policies-for-your-enterprise/enforcing-policies-for-security-settings-in-your-enterprise)."
#### 2. Enabling and enforcing SAML single sign-on for organizations in your enterprise account
You can centrally manage access to your enterprise's resources, organization membership and team membership using your IdP and SAM single sign-on (SSO). Enterprise owners can enable SAML SSO across all organizations owned by an enterprise account. For more information, see "[About identity and access management for your enterprise](/enterprise-cloud@latest/admin/authentication/managing-identity-and-access-for-your-enterprise/about-identity-and-access-management-for-your-enterprise)."

#### 3. Managing team synchronization
You can enable and manage team synchronization between an identity provider (IdP) and {% data variables.product.prodname_dotcom %} to allow organizations owned by your enterprise account to manage team membership with IdP groups. For more information, see "[Managing team synchronization for organizations in your enterprise account](/enterprise-cloud@latest/admin/authentication/managing-identity-and-access-for-your-enterprise/managing-team-synchronization-for-organizations-in-your-enterprise)."

#### 4. Enforcing policies for Advanced Security features in your enterprise account
{% data reusables.getting-started.enterprise-advanced-security %}

## Part 5: Managing organization and enterprise level policies and settings

### Managing settings for a single organization
To manage and moderate your organization, you can set organization policies, manage permissions for repository changes, and use organization-level community health files.
#### 1. Managing organization policies
{% data reusables.getting-started.managing-org-policies %}
#### 2. Managing repository changes
{% data reusables.getting-started.managing-repo-changes %}
#### 3. Using organization-level community health files and moderation tools
{% data reusables.getting-started.using-org-community-files-and-moderation-tools %}

### Managing settings for an enterprise account
To manage and moderate your enterprise, you can set policies for organizations within the enterprise, view audit logs, configure webhooks, and restrict email notifications.
#### 1. Managing policies for organizations in your enterprise account

You can choose to enforce a number of policies for all organizations owned by your enterprise, or choose to allow these policies to be set in each organization. Types of policies you can enforce include repository management, project board, and team policies. For more information, see "[Setting policies for your enterprise](/enterprise-cloud@latest/admin/policies)."
#### 2. Viewing audit logs, configuring webhooks, and restricting email notifications for your enterprise
You can view actions from all of the organizations owned by your enterprise account in the enterprise audit log. You can also configure webhooks to receive events from organizations owned by your enterprise account. For more information, see "[Reviewing audit logs for your enterprise](/enterprise-cloud@latest/admin/monitoring-activity-in-your-enterprise/reviewing-audit-logs-for-your-enterprise)" and "[Monitoring your enterprise](/enterprise-cloud@latest/admin/monitoring-activity-in-your-enterprise)."

You can also restrict email notifications for your enterprise account so that enterprise members can only use an email address in a verified or approved domain to receive notifications. For more information, see "[Restricting email notifications for your enterprise](/enterprise-cloud@latest/admin/policies/enforcing-policies-for-your-enterprise/restricting-email-notifications-for-your-enterprise)."

## Part 6: Customizing and automating your organization or enterprise's work on {% data variables.product.prodname_dotcom %}
Members of your organization or enterprise can use tools from the {% data variables.product.prodname_marketplace %}, the {% ifversion fpt or ghec %}{% data variables.product.prodname_dotcom %}{% else %}{% data variables.product.product_name %}{% endif %} API, and existing {% data variables.product.product_name %} features to customize and automate your work.

### 1. Using {% data variables.product.prodname_marketplace %}
{% data reusables.getting-started.marketplace %}
### 2. Using the {% ifversion fpt or ghec %}{% data variables.product.prodname_dotcom %}{% else %}{% data variables.product.product_name %}{% endif %} API
{% data reusables.getting-started.api %}
### 3. Building {% data variables.product.prodname_actions %}
{% data reusables.getting-started.actions %}
### 4. Publishing and managing {% data variables.product.prodname_registry %} 
{% data reusables.getting-started.packages %}
### 5. Using {% data variables.product.prodname_pages %}
{% data variables.product.prodname_pages %} is a static site hosting service that takes HTML, CSS, and JavaScript files straight from a repository and publishes a website. You can manage the publication of {% data variables.product.prodname_pages %} sites at the organization level. For more information, see  "[Managing the publication of {% data variables.product.prodname_pages %} sites for your organization](/organizations/managing-organization-settings/managing-the-publication-of-github-pages-sites-for-your-organization)" and "[About {% data variables.product.prodname_pages %}](/pages/getting-started-with-github-pages/about-github-pages)."
## Part 7: Participating in {% data variables.product.prodname_dotcom %}'s community

Members of your organization or enterprise can use GitHub's learning and support resources to get the help they need. You can also support the open source community. 

### 1. Reading about {% data variables.product.prodname_ghe_cloud %} on {% data variables.product.prodname_docs %}

{% data reusables.docs.ghec-docs %}

{% data reusables.enterprise.best-practices %}

### 2. Learning with {% data variables.product.prodname_learning %}
Members of your organization or enterprise can learn new skills by completing fun, realistic projects in your very own GitHub repository with [{% data variables.product.prodname_learning %}](https://skills.github.com/). Each course is a hands-on lesson created by the GitHub community and taught by a friendly bot.

For more information, see "[Git and {% data variables.product.prodname_dotcom %} learning resources](/github/getting-started-with-github/quickstart/git-and-github-learning-resources)."
### 3. Supporting the open source community
{% data reusables.getting-started.sponsors %}

### 4. Contacting {% data variables.contact.github_support %}
{% data reusables.getting-started.contact-support %}

{% data variables.product.prodname_ghe_cloud %} allows you to submit priority support requests with a target eight-hour response time. For more information, see "[{% data variables.product.prodname_ghe_cloud %} support](/github/working-with-github-support/github-enterprise-cloud-support)."
