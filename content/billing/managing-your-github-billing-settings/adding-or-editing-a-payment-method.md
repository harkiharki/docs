---
title: Adding or editing a payment method
intro: You can add a payment method to your account or update your account's existing payment method at any time.
redirect_from:
  - /github/setting-up-and-managing-billing-and-payments-on-github/adding-or-editing-a-payment-method
  - /articles/updating-your-personal-account-s-payment-method
  - /articles/how-do-i-update-my-credit-card
  - /articles/updating-your-account-s-credit-card
  - /articles/updating-your-personal-account-s-credit-card
  - /articles/updating-your-personal-account-s-paypal-information
  - /articles/does-github-provide-invoicing
  - /articles/switching-payment-methods-for-your-personal-account
  - /articles/paying-for-your-github-organization-account
  - /articles/updating-your-organization-s-credit-card
  - /articles/updating-your-organization-s-paypal-information
  - /articles/updating-your-organization-s-payment-method
  - /articles/switching-payment-methods-for-your-organization
  - /articles/adding-or-editing-a-payment-method
  - /github/setting-up-and-managing-billing-and-payments-on-github/managing-your-github-billing-settings/adding-or-editing-a-payment-method
versions:
  fpt: '*'
  ghec: '*'
type: how_to
topics:
  - Organizations
  - User account
shortTitle: Manage a payment method
---
{% data reusables.dotcom_billing.payment-methods %} {% data reusables.dotcom_billing.same-payment-method %}

We don't provide invoicing or support purchase orders for personal accounts. We email receipts monthly or yearly on your account's billing date. If your company, country, or accountant requires your receipts to provide more detail, you can also [add extra information](/billing/managing-your-github-billing-settings/adding-information-to-your-receipts) to your receipts.

## Updating your personal account's payment method

{% data reusables.user-settings.billing_plans %}
{% data reusables.dotcom_billing.update_payment_method %}
1. If your account has existing billing information that you want to update, click **Edit**.
![Screenshot of the "Payment information" section. Next to "Billing information", a link, labeled "Edit", is highlighted with an orange outline.](/assets/images/help/billing/billing-information-edit-button.png)
{% data reusables.dotcom_billing.enter-billing-info %}
1. If your account has an existing payment method that you want to update, click **Edit**.
![Screenshot of the "Payment method" section. Next to "Payment method", a link, labeled "Edit", is highlighted with an orange outline.](/assets/images/help/billing/billing-payment-method-edit-button.png)
{% data reusables.dotcom_billing.enter-payment-info %}

## Updating your organization's payment method

{% data reusables.dotcom_billing.org-billing-perms %}

If your organization is outside of the US or if you're using a corporate checking account to pay for {% data variables.product.product_name %}, PayPal could be a helpful method of payment.

{% data reusables.organizations.billing-settings %}
{% data reusables.dotcom_billing.update_payment_method %}
1. If your account has an existing credit card that you want to update, click **New Card**.
![Screenshot of the "Payment method" section. Below some card details, a link, labeled "New Card", is highlighted with an orange outline.](/assets/images/help/billing/billing-new-card-button.png)
{% data reusables.dotcom_billing.enter-payment-info %}
