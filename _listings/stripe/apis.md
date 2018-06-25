---
name: Stripe
x-slug: stripe
description: Online payment processing for internet businesses. Stripe is a suite
  of payment APIs that powers commerce for online businesses of all sizes, including
  fraud prevention, and subscription management. Use Stripes payment platform to accept
  and process p...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
x-kinRank: "10"
x-alexaRank: "1914"
tags: Stripe
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/apis.md
specificationVersion: "0.14"
apis:
- name: Stripe Add 3d Secure
  x-api-slug: stripe
  description: Post 3d, Secure
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///3d_secure
  tags: 3d, Secure
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/3d-secure-post-openapi.md
- name: Stripe Get 3d Secure Three D Secure
  x-api-slug: stripe
  description: Get 3d, Secure, Three, D, Secure
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///3d_secure/{three_d_secure}
  tags: 3d, Secure, Three, D, Secure
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/3d-securethree-d-secure-get-openapi.md
- name: Stripe Delete Account
  x-api-slug: stripe
  description: With Connect, you may delete Custom accounts you manage.Custom accounts
    created using test-mode keys can be deleted at any time. Custom accounts created
    using live-mode keys may only be deleted once all balances are zero.If you are
    looking to close your own account, use the data tab in your account settings instead.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///account
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/account-delete-openapi.md
- name: Stripe Get Account
  x-api-slug: stripe
  description: Retrieves the details of the account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///account
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/account-get-openapi.md
- name: Stripe Add Account
  x-api-slug: stripe
  description: Updates a connected Express or Custom account by setting the values
    of the parameters passed. Any parameters not provided are left unchanged. To update
    your own account, use the Dashboard.Refer to our Connect documentation to learn
    more about updating accounts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///account
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/account-post-openapi.md
- name: Stripe Add Account Bank Accounts
  x-api-slug: stripe
  description: Post Account, Bank, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///account/bank_accounts
  tags: Account, Bank, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountbank-accounts-post-openapi.md
- name: Stripe Delete Account Bank Accounts
  x-api-slug: stripe
  description: Delete Account, Bank, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///account/bank_accounts/{id}
  tags: Account, Bank, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountbank-accountsid-delete-openapi.md
- name: Stripe Get Account Bank Accounts
  x-api-slug: stripe
  description: Get Account, Bank, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///account/bank_accounts/{id}
  tags: Account, Bank, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountbank-accountsid-get-openapi.md
- name: Stripe Add Account Bank Accounts
  x-api-slug: stripe
  description: Updates the metadata of a bank account belonging to a Custom account,
    and optionally sets it as the default for its currency. Other bank account details
    are not editable by design.You can re-enable a disabled bank account by performing
    an update call without providing any arguments or changes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///account/bank_accounts/{id}
  tags: Account, Bank, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountbank-accountsid-post-openapi.md
- name: Stripe Get Account External Accounts
  x-api-slug: stripe
  description: Get Account, External, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///account/external_accounts
  tags: Account, External, Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountexternal-accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountexternal-accounts-get-openapi.md
- name: Stripe Add Account External Accounts
  x-api-slug: stripe
  description: Post Account, External, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///account/external_accounts
  tags: Account, External, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountexternal-accounts-post-openapi.md
- name: Stripe Delete Account External Accounts
  x-api-slug: stripe
  description: Delete Account, External, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///account/external_accounts/{id}
  tags: Account, External, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountexternal-accountsid-delete-openapi.md
- name: Stripe Get Account External Accounts
  x-api-slug: stripe
  description: Get Account, External, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///account/external_accounts/{id}
  tags: Account, External, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountexternal-accountsid-get-openapi.md
- name: Stripe Add Account External Accounts
  x-api-slug: stripe
  description: Updates the metadata of a bank account belonging to a Custom account,
    and optionally sets it as the default for its currency. Other bank account details
    are not editable by design.You can re-enable a disabled bank account by performing
    an update call without providing any arguments or changes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///account/external_accounts/{id}
  tags: Account, External, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountexternal-accountsid-post-openapi.md
- name: Stripe Add Account Login Links
  x-api-slug: stripe
  description: Creates a single-use login link for an Express account to access their
    Stripe dashboard.You may only create login links for Express accounts connected
    to your platform.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///account/login_links
  tags: Account, Login, Links
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountlogin-links-post-openapi.md
- name: Stripe Put Account Logout
  x-api-slug: stripe
  description: Invalidates all sessions for a light account, for a platform to use
    during platform logout.You may only log out Express accounts connected to your
    platform.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///account/logout
  tags: Account, Logout
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountlogout-put-openapi.md
- name: Stripe Get Accounts
  x-api-slug: stripe
  description: "Returns a list of accounts connected to your platform via Connect.
    If you\u2019re not a platform, the list is empty."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts
  tags: Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accounts-get-openapi.md
- name: Stripe Add Accounts
  x-api-slug: stripe
  description: Post Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts
  tags: Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accounts-post-openapi.md
- name: Stripe Delete Accounts Account
  x-api-slug: stripe
  description: With Connect, you may delete Custom accounts you manage.Custom accounts
    created using test-mode keys can be deleted at any time. Custom accounts created
    using live-mode keys may only be deleted once all balances are zero.If you are
    looking to close your own account, use the data tab in your account settings instead.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}
  tags: Accounts, Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountsaccount-delete-openapi.md
- name: Stripe Get Accounts Account
  x-api-slug: stripe
  description: Retrieves the details of the account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}
  tags: Accounts, Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountsaccount-get-openapi.md
- name: Stripe Add Accounts Account
  x-api-slug: stripe
  description: Updates a connected Express or Custom account by setting the values
    of the parameters passed. Any parameters not provided are left unchanged. To update
    your own account, use the Dashboard.Refer to our Connect documentation to learn
    more about updating accounts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}
  tags: Accounts, Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountsaccount-post-openapi.md
- name: Stripe Add Accounts Account Bank Accounts
  x-api-slug: stripe
  description: Post Accounts, Account, Bank, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}/bank_accounts
  tags: Accounts, Account, Bank, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountsaccountbank-accounts-post-openapi.md
- name: Stripe Delete Accounts Account Bank Accounts
  x-api-slug: stripe
  description: Delete Accounts, Account, Bank, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}/bank_accounts/{id}
  tags: Accounts, Account, Bank, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountsaccountbank-accountsid-delete-openapi.md
- name: Stripe Get Accounts Account Bank Accounts
  x-api-slug: stripe
  description: Get Accounts, Account, Bank, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}/bank_accounts/{id}
  tags: Accounts, Account, Bank, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountsaccountbank-accountsid-get-openapi.md
- name: Stripe Add Accounts Account Bank Accounts
  x-api-slug: stripe
  description: Updates the metadata of a bank account belonging to a Custom account,
    and optionally sets it as the default for its currency. Other bank account details
    are not editable by design.You can re-enable a disabled bank account by performing
    an update call without providing any arguments or changes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}/bank_accounts/{id}
  tags: Accounts, Account, Bank, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountsaccountbank-accountsid-post-openapi.md
- name: Stripe Get Accounts Account External Accounts
  x-api-slug: stripe
  description: Get Accounts, Account, External, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}/external_accounts
  tags: Accounts, Account, External, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountsaccountexternal-accounts-get-openapi.md
- name: Stripe Add Accounts Account External Accounts
  x-api-slug: stripe
  description: Post Accounts, Account, External, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}/external_accounts
  tags: Accounts, Account, External, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountsaccountexternal-accounts-post-openapi.md
- name: Stripe Delete Accounts Account External Accounts
  x-api-slug: stripe
  description: Delete Accounts, Account, External, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}/external_accounts/{id}
  tags: Accounts, Account, External, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountsaccountexternal-accountsid-delete-openapi.md
- name: Stripe Get Accounts Account External Accounts
  x-api-slug: stripe
  description: Get Accounts, Account, External, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}/external_accounts/{id}
  tags: Accounts, Account, External, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountsaccountexternal-accountsid-get-openapi.md
- name: Stripe Add Accounts Account External Accounts
  x-api-slug: stripe
  description: Updates the metadata of a bank account belonging to a Custom account,
    and optionally sets it as the default for its currency. Other bank account details
    are not editable by design.You can re-enable a disabled bank account by performing
    an update call without providing any arguments or changes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}/external_accounts/{id}
  tags: Accounts, Account, External, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountsaccountexternal-accountsid-post-openapi.md
- name: Stripe Add Accounts Account Login Links
  x-api-slug: stripe
  description: Creates a single-use login link for an Express account to access their
    Stripe dashboard.You may only create login links for Express accounts connected
    to your platform.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}/login_links
  tags: Accounts, Account, Login, Links
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountsaccountlogin-links-post-openapi.md
- name: Stripe Put Accounts Account Logout
  x-api-slug: stripe
  description: Invalidates all sessions for a light account, for a platform to use
    during platform logout.You may only log out Express accounts connected to your
    platform.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}/logout
  tags: Accounts, Account, Logout
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountsaccountlogout-put-openapi.md
- name: Stripe Add Accounts Account Reject
  x-api-slug: stripe
  description: With Connect, you may flag accounts as suspicious.Test-mode Custom
    and Express accounts can be rejected at any time. Accounts created using live-mode
    keys may only be rejected once all balances are zero.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}/reject
  tags: Accounts, Account, Reject
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/accountsaccountreject-post-openapi.md
- name: Stripe Get Apple Pay Domains
  x-api-slug: stripe
  description: Get Apple, Pay, Domains
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///apple_pay/domains
  tags: Apple, Pay, Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/apple-paydomains-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/apple-paydomains-get-openapi.md
- name: Stripe Add Apple Pay Domains
  x-api-slug: stripe
  description: Post Apple, Pay, Domains
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///apple_pay/domains
  tags: Apple, Pay, Domains
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/apple-paydomains-post-openapi.md
- name: Stripe Delete Apple Pay Domains Domain
  x-api-slug: stripe
  description: Delete Apple, Pay, Domains, Domain
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///apple_pay/domains/{domain}
  tags: Apple, Pay, Domains, Domain
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/apple-paydomainsdomain-delete-openapi.md
- name: Stripe Get Apple Pay Domains Domain
  x-api-slug: stripe
  description: Get Apple, Pay, Domains, Domain
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///apple_pay/domains/{domain}
  tags: Apple, Pay, Domains, Domain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/apple-paydomainsdomain-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/apple-paydomainsdomain-get-openapi.md
- name: Stripe Get Application Fees
  x-api-slug: stripe
  description: "Returns a list of application fees you\u2019ve previously collected.
    The application fees are returned in sorted order, with the most recent fees appearing
    first."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///application_fees
  tags: Application, Fees
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/application-fees-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/application-fees-get-openapi.md
- name: Stripe Get Application Fees Fee Refunds
  x-api-slug: stripe
  description: By default, you can see the 10 most recent refunds stored directly
    on the application fee object, but you can also retrieve details about a specific
    refund stored on the application fee.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///application_fees/{fee}/refunds/{id}
  tags: Application, Fees, Fee, Refunds
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/application-feesfeerefundsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/application-feesfeerefundsid-get-openapi.md
- name: Stripe Add Application Fees Fee Refunds
  x-api-slug: stripe
  description: Updates the specified application fee refund by setting the values
    of the parameters passed. Any parameters not provided will be left unchanged.This
    request only accepts metadata as an argument.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///application_fees/{fee}/refunds/{id}
  tags: Application, Fees, Fee, Refunds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/application-feesfeerefundsid-post-openapi.md
- name: Stripe Get Application Fees
  x-api-slug: stripe
  description: Retrieves the details of an application fee that your account has collected.
    The same information is returned when refunding the application fee.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///application_fees/{id}
  tags: Application, Fees
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/application-feesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/application-feesid-get-openapi.md
- name: Stripe Add Application Fees  Refund
  x-api-slug: stripe
  description: Post Application, Fees, , Refund
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///application_fees/{id}/refund
  tags: Application, Fees, , Refund
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/application-feesidrefund-post-openapi.md
- name: Stripe Get Application Fees  Refunds
  x-api-slug: stripe
  description: You can see a list of the refunds belonging to a specific application
    fee. Note that the 10 most recent refunds are always available by default on the
    application fee object. If you need more than those 10, you can use this API method
    and the limit and starting_after parameters to page through additional refunds.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///application_fees/{id}/refunds
  tags: Application, Fees, , Refunds
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/application-feesidrefunds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/application-feesidrefunds-get-openapi.md
- name: Stripe Add Application Fees  Refunds
  x-api-slug: stripe
  description: Post Application, Fees, , Refunds
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///application_fees/{id}/refunds
  tags: Application, Fees, , Refunds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/application-feesidrefunds-post-openapi.md
- name: Stripe Get Balance
  x-api-slug: stripe
  description: Retrieves the current account balance, based on the authentication
    that was used to make the request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///balance
  tags: Balance
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/balance-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/balance-get-openapi.md
- name: Stripe Get Balance History
  x-api-slug: stripe
  description: Returns a list of transactions that have contributed to the Stripe
    account balance (e.g., charges, transfers, and so forth). The transactions are
    returned in sorted order, with the most recent transactions appearing first.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///balance/history
  tags: Balance, History
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/balancehistory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/balancehistory-get-openapi.md
- name: Stripe Get Balance History
  x-api-slug: stripe
  description: Retrieves the balance transaction with the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///balance/history/{id}
  tags: Balance, History
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/balancehistoryid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/balancehistoryid-get-openapi.md
- name: Stripe Get Bitcoin Receivers
  x-api-slug: stripe
  description: Returns a list of your receivers. Receivers are returned sorted by
    creation date, with the most recently created receivers appearing first.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///bitcoin/receivers
  tags: Bitcoin, Receivers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/bitcoinreceivers-get-openapi.md
- name: Stripe Get Bitcoin Receivers
  x-api-slug: stripe
  description: Retrieves the Bitcoin receiver with the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///bitcoin/receivers/{id}
  tags: Bitcoin, Receivers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/bitcoinreceiversid-get-openapi.md
- name: Stripe Get Bitcoin Receivers Receiver Transactions
  x-api-slug: stripe
  description: Get Bitcoin, Receivers, Receiver, Transactions
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///bitcoin/receivers/{receiver}/transactions
  tags: Bitcoin, Receivers, Receiver, Transactions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/bitcoinreceiversreceivertransactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/bitcoinreceiversreceivertransactions-get-openapi.md
- name: Stripe Get Bitcoin Transactions
  x-api-slug: stripe
  description: Get Bitcoin, Transactions
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///bitcoin/transactions
  tags: Bitcoin, Transactions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/bitcointransactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/bitcointransactions-get-openapi.md
- name: Stripe Get Charges
  x-api-slug: stripe
  description: "Returns a list of charges you\u2019ve previously created. The charges
    are returned in sorted order, with the most recent charges appearing first."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges
  tags: Charges
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/charges-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/charges-get-openapi.md
- name: Stripe Add Charges
  x-api-slug: stripe
  description: Post Charges
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges
  tags: Charges
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/charges-post-openapi.md
- name: Stripe Get Charges Charge
  x-api-slug: stripe
  description: Retrieves the details of a charge that has previously been created.
    Supply the unique charge ID that was returned from your previous request, and
    Stripe will return the corresponding charge information. The same information
    is returned when creating or refunding the charge.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}
  tags: Charges, Charge
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/chargescharge-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/chargescharge-get-openapi.md
- name: Stripe Add Charges Charge
  x-api-slug: stripe
  description: Updates the specified charge by setting the values of the parameters
    passed. Any parameters not provided will be left unchanged.This request accepts
    only the customer, description, fraud_details, metadata, receipt_email, and shipping
    arguments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}
  tags: Charges, Charge
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/chargescharge-post-openapi.md
- name: Stripe Add Charges Charge Capture
  x-api-slug: stripe
  description: Capture the payment of an existing, uncaptured, charge. This is the
    second half of the two-step payment flow, where first you created a charge with
    the capture option set to false.Uncaptured payments expire exactly seven days
    after they are created. If they are not captured by that point in time, they will
    be marked as refunded and will no longer be capturable.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/capture
  tags: Charges, Charge, Capture
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/chargeschargecapture-post-openapi.md
- name: Stripe Get Charges Charge Dispute
  x-api-slug: stripe
  description: Get Charges, Charge, Dispute
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/dispute
  tags: Charges, Charge, Dispute
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/chargeschargedispute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/chargeschargedispute-get-openapi.md
- name: Stripe Add Charges Charge Dispute
  x-api-slug: stripe
  description: Post Charges, Charge, Dispute
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/dispute
  tags: Charges, Charge, Dispute
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/chargeschargedispute-post-openapi.md
- name: Stripe Add Charges Charge Dispute Close
  x-api-slug: stripe
  description: Post Charges, Charge, Dispute, Close
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/dispute/close
  tags: Charges, Charge, Dispute, Close
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/chargeschargedisputeclose-post-openapi.md
- name: Stripe Add Charges Charge Refund
  x-api-slug: stripe
  description: Post Charges, Charge, Refund
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/refund
  tags: Charges, Charge, Refund
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/chargeschargerefund-post-openapi.md
- name: Stripe Get Charges Charge Refunds
  x-api-slug: stripe
  description: You can see a list of the refunds belonging to a specific charge. Note
    that the 10 most recent refunds are always available by default on the charge
    object. If you need more than those 10, you can use this API method and the limit
    and starting_after parameters to page through additional refunds.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/refunds
  tags: Charges, Charge, Refunds
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/chargeschargerefunds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/chargeschargerefunds-get-openapi.md
- name: Stripe Add Charges Charge Refunds
  x-api-slug: stripe
  description: Post Charges, Charge, Refunds
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/refunds
  tags: Charges, Charge, Refunds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/chargeschargerefunds-post-openapi.md
- name: Stripe Get Charges Charge Refunds Refund
  x-api-slug: stripe
  description: Get Charges, Charge, Refunds, Refund
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/refunds/{refund}
  tags: Charges, Charge, Refunds, Refund
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/chargeschargerefundsrefund-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/chargeschargerefundsrefund-get-openapi.md
- name: Stripe Add Charges Charge Refunds Refund
  x-api-slug: stripe
  description: Post Charges, Charge, Refunds, Refund
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/refunds/{refund}
  tags: Charges, Charge, Refunds, Refund
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/chargeschargerefundsrefund-post-openapi.md
- name: Stripe Get Country Specs
  x-api-slug: stripe
  description: Lists all Country Spec objects available in the API.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///country_specs
  tags: Country, Specs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/country-specs-get-openapi.md
- name: Stripe Get Country Specs Country
  x-api-slug: stripe
  description: Returns a Country Spec for a given Country code.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///country_specs/{country}
  tags: Country, Specs, Country
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/country-specscountry-get-openapi.md
- name: Stripe Get Coupons
  x-api-slug: stripe
  description: Returns a list of your coupons.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///coupons
  tags: Coupons
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/coupons-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/coupons-get-openapi.md
- name: Stripe Add Coupons
  x-api-slug: stripe
  description: "You can create coupons easily via the coupon management page of the
    Stripe dashboard. Coupon creation is also accessible via the API if you need to
    create coupons on the fly.A coupon has either a percent_off or an amount_off and
    currency. If you set an amount_off, that amount will be subtracted from any invoice\u2019s
    subtotal. For example, an invoice with a subtotal of 100 will have a final total
    of 0 if a coupon with an amount_off of 200 is applied to it and an invoice with
    a subtotal of 300 will have a final total of 100 if a coupon with an amount_off
    of 200 is applied to it."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///coupons
  tags: Coupons
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/coupons-post-openapi.md
- name: Stripe Delete Coupons Coupon
  x-api-slug: stripe
  description: "You can delete coupons via the coupon management page of the Stripe
    dashboard. However, deleting a coupon does not affect any customers who have already
    applied the coupon; it means that new customers can\u2019t redeem the coupon.
    You can also delete coupons via the API."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///coupons/{coupon}
  tags: Coupons, Coupon
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/couponscoupon-delete-openapi.md
- name: Stripe Get Coupons Coupon
  x-api-slug: stripe
  description: Retrieves the coupon with the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///coupons/{coupon}
  tags: Coupons, Coupon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/couponscoupon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/couponscoupon-get-openapi.md
- name: Stripe Add Coupons Coupon
  x-api-slug: stripe
  description: Updates the metadata of a coupon. Other coupon details (currency, duration,
    amount_off) are, by design, not editable.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///coupons/{coupon}
  tags: Coupons, Coupon
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/couponscoupon-post-openapi.md
- name: Stripe Get Customers
  x-api-slug: stripe
  description: Returns a list of your customers. The customers are returned sorted
    by creation date, with the most recent customers appearing first.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers
  tags: Customers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customers-get-openapi.md
- name: Stripe Add Customers
  x-api-slug: stripe
  description: Creates a new customer object.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers
  tags: Customers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customers-post-openapi.md
- name: Stripe Delete Customers Customer
  x-api-slug: stripe
  description: Permanently deletes a customer. It cannot be undone. Also immediately
    cancels any active subscriptions on the customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}
  tags: Customers, Customer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomer-delete-openapi.md
- name: Stripe Get Customers Customer
  x-api-slug: stripe
  description: Retrieves the details of an existing customer. You need only supply
    the unique customer identifier that was returned upon customer creation.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}
  tags: Customers, Customer
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomer-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomer-get-openapi.md
- name: Stripe Add Customers Customer
  x-api-slug: stripe
  description: Post Customers, Customer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}
  tags: Customers, Customer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomer-post-openapi.md
- name: Stripe Get Customers Customer Bank Accounts
  x-api-slug: stripe
  description: You can see a list of the bank accounts belonging to a Customer. Note
    that the 10 most recent sources are always available by default on the Customer.
    If you need more than those 10, you can use this API method and the limit and
    starting_after parameters to page through additional bank accounts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/bank_accounts
  tags: Customers, Customer, Bank, Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomerbank-accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomerbank-accounts-get-openapi.md
- name: Stripe Add Customers Customer Bank Accounts
  x-api-slug: stripe
  description: Post Customers, Customer, Bank, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/bank_accounts
  tags: Customers, Customer, Bank, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomerbank-accounts-post-openapi.md
- name: Stripe Delete Customers Customer Bank Accounts
  x-api-slug: stripe
  description: Delete Customers, Customer, Bank, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/bank_accounts/{id}
  tags: Customers, Customer, Bank, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomerbank-accountsid-delete-openapi.md
- name: Stripe Get Customers Customer Bank Accounts
  x-api-slug: stripe
  description: By default, you can see the 10 most recent sources stored on a Customer
    directly on the object, but you can also retrieve details about a specific bank
    account stored on the Stripe account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/bank_accounts/{id}
  tags: Customers, Customer, Bank, Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomerbank-accountsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomerbank-accountsid-get-openapi.md
- name: Stripe Add Customers Customer Bank Accounts
  x-api-slug: stripe
  description: Post Customers, Customer, Bank, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/bank_accounts/{id}
  tags: Customers, Customer, Bank, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomerbank-accountsid-post-openapi.md
- name: Stripe Add Customers Customer Bank Accounts  Verify
  x-api-slug: stripe
  description: Post Customers, Customer, Bank, Accounts, , Verify
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/bank_accounts/{id}/verify
  tags: Customers, Customer, Bank, Accounts, , Verify
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomerbank-accountsidverify-post-openapi.md
- name: Stripe Get Customers Customer Cards
  x-api-slug: stripe
  description: Get Customers, Customer, Cards
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/cards
  tags: Customers, Customer, Cards
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomercards-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomercards-get-openapi.md
- name: Stripe Add Customers Customer Cards
  x-api-slug: stripe
  description: Post Customers, Customer, Cards
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/cards
  tags: Customers, Customer, Cards
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomercards-post-openapi.md
- name: Stripe Delete Customers Customer Cards
  x-api-slug: stripe
  description: Delete Customers, Customer, Cards
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/cards/{id}
  tags: Customers, Customer, Cards
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomercardsid-delete-openapi.md
- name: Stripe Get Customers Customer Cards
  x-api-slug: stripe
  description: Get Customers, Customer, Cards
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/cards/{id}
  tags: Customers, Customer, Cards
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomercardsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomercardsid-get-openapi.md
- name: Stripe Add Customers Customer Cards
  x-api-slug: stripe
  description: Post Customers, Customer, Cards
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/cards/{id}
  tags: Customers, Customer, Cards
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomercardsid-post-openapi.md
- name: Stripe Delete Customers Customer Discount
  x-api-slug: stripe
  description: Removes the currently applied discount on a customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/discount
  tags: Customers, Customer, Discount
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomerdiscount-delete-openapi.md
- name: Stripe Get Customers Customer Discount
  x-api-slug: stripe
  description: Get Customers, Customer, Discount
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/discount
  tags: Customers, Customer, Discount
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomerdiscount-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomerdiscount-get-openapi.md
- name: Stripe Get Customers Customer Sources
  x-api-slug: stripe
  description: Get Customers, Customer, Sources
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/sources
  tags: Customers, Customer, Sources
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomersources-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomersources-get-openapi.md
- name: Stripe Add Customers Customer Sources
  x-api-slug: stripe
  description: Post Customers, Customer, Sources
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/sources
  tags: Customers, Customer, Sources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomersources-post-openapi.md
- name: Stripe Delete Customers Customer Sources
  x-api-slug: stripe
  description: Delete Customers, Customer, Sources
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/sources/{id}
  tags: Customers, Customer, Sources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomersourcesid-delete-openapi.md
- name: Stripe Get Customers Customer Sources
  x-api-slug: stripe
  description: Get Customers, Customer, Sources
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/sources/{id}
  tags: Customers, Customer, Sources
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomersourcesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomersourcesid-get-openapi.md
- name: Stripe Add Customers Customer Sources
  x-api-slug: stripe
  description: Post Customers, Customer, Sources
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/sources/{id}
  tags: Customers, Customer, Sources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomersourcesid-post-openapi.md
- name: Stripe Add Customers Customer Sources  Verify
  x-api-slug: stripe
  description: Post Customers, Customer, Sources, , Verify
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/sources/{id}/verify
  tags: Customers, Customer, Sources, , Verify
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomersourcesidverify-post-openapi.md
- name: Stripe Get Customers Customer Subscriptions
  x-api-slug: stripe
  description: "You can see a list of the customer\u2019s active subscriptions. Note
    that the 10 most recent active subscriptions are always available by default on
    the customer object. If you need more than those 10, you can use the limit and
    starting_after parameters to page through additional subscriptions."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/subscriptions
  tags: Customers, Customer, Subscriptions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomersubscriptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomersubscriptions-get-openapi.md
- name: Stripe Add Customers Customer Subscriptions
  x-api-slug: stripe
  description: Creates a new subscription on an existing customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/subscriptions
  tags: Customers, Customer, Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomersubscriptions-post-openapi.md
- name: Stripe Delete Customers Customer Subscriptions Subscription Exposed
  x-api-slug: stripe
  description: "Cancels a customer\u2019s subscription. If you set the at_period_end
    parameter to true, the subscription will remain active until the end of the period,
    at which point it will be canceled and not renewed. By default, the subscription
    is terminated immediately. In either case, the customer will not be charged again
    for the subscription. Note, however, that any pending invoice items that you\u2019ve
    created will still be charged for at the end of the period unless manually deleted.
    If you\u2019ve set the subscription to cancel at period end, any pending prorations
    will also be left in place and collected at the end of the period, but if the
    subscription is set to cancel immediately, pending prorations will be removed.By
    default, all unpaid invoices for the customer will be closed upon subscription
    cancellation. We do this in order to prevent unexpected payment attempts once
    the customer has canceled a subscription. However, you can reopen the invoices
    manually after subscription cancellation to have us proceed with payment collection,
    or you could even re-attempt payment yourself on all unpaid invoices before allowing
    the customer to cancel the subscription at all."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/subscriptions/{subscription_exposed_id}
  tags: Customers, Customer, Subscriptions, Subscription, Exposed
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomersubscriptionssubscription-exposed-id-delete-openapi.md
- name: Stripe Get Customers Customer Subscriptions Subscription Exposed
  x-api-slug: stripe
  description: Get Customers, Customer, Subscriptions, Subscription, Exposed
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/subscriptions/{subscription_exposed_id}
  tags: Customers, Customer, Subscriptions, Subscription, Exposed
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomersubscriptionssubscription-exposed-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomersubscriptionssubscription-exposed-id-get-openapi.md
- name: Stripe Add Customers Customer Subscriptions Subscription Exposed
  x-api-slug: stripe
  description: Updates an existing subscription on a customer to match the specified
    parameters. When changing plans or quantities, we will optionally prorate the
    price we charge next month to make up for any price changes. To preview how the
    proration will be calculated, use the upcoming invoice endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/subscriptions/{subscription_exposed_id}
  tags: Customers, Customer, Subscriptions, Subscription, Exposed
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomersubscriptionssubscription-exposed-id-post-openapi.md
- name: Stripe Delete Customers Customer Subscriptions Subscription Exposed  Discount
  x-api-slug: stripe
  description: Delete Customers, Customer, Subscriptions, Subscription, Exposed, ,
    Discount
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/subscriptions/{subscription_exposed_id}/discount
  tags: Customers, Customer, Subscriptions, Subscription, Exposed, , Discount
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomersubscriptionssubscription-exposed-iddiscount-delete-openapi.md
- name: Stripe Get Customers Customer Subscriptions Subscription Exposed  Discount
  x-api-slug: stripe
  description: Get Customers, Customer, Subscriptions, Subscription, Exposed, , Discount
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/subscriptions/{subscription_exposed_id}/discount
  tags: Customers, Customer, Subscriptions, Subscription, Exposed, , Discount
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomersubscriptionssubscription-exposed-iddiscount-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/customerscustomersubscriptionssubscription-exposed-iddiscount-get-openapi.md
- name: Stripe Get Disputes
  x-api-slug: stripe
  description: Returns a list of your disputes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///disputes
  tags: Disputes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/disputes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/disputes-get-openapi.md
- name: Stripe Get Disputes Dispute
  x-api-slug: stripe
  description: Retrieves the dispute with the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///disputes/{dispute}
  tags: Disputes, Dispute
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/disputesdispute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/disputesdispute-get-openapi.md
- name: Stripe Add Disputes Dispute
  x-api-slug: stripe
  description: "When you get a dispute, contacting your customer is always the best
    first step. If that doesn\u2019t work, you can submit evidence in order to help
    us resolve the dispute in your favor. You can do this in your dashboard, but if
    you prefer, you can use the API to submit evidence programmatically.Depending
    on your dispute type, different evidence fields will give you a better chance
    of winning your dispute. You may want to consult our guide to dispute types to
    help you figure out which evidence fields to provide."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///disputes/{dispute}
  tags: Disputes, Dispute
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/disputesdispute-post-openapi.md
- name: Stripe Add Disputes Dispute Close
  x-api-slug: stripe
  description: "Closing the dispute for a charge indicates that you do not have any
    evidence to submit and are essentially \u2018dismissing\u2019 the dispute, acknowledging
    it as lostThe status of the dispute will change from needs_response to lost. Closing
    a dispute is irreversible."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///disputes/{dispute}/close
  tags: Disputes, Dispute, Close
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/disputesdisputeclose-post-openapi.md
- name: Stripe Add Ephemeral Keys
  x-api-slug: stripe
  description: Creates a short-lived API key for a given resource.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///ephemeral_keys
  tags: Ephemeral, Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/ephemeral-keys-post-openapi.md
- name: Stripe Delete Ephemeral Keys Key
  x-api-slug: stripe
  description: Invalidates a short-lived API key for a given resource.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///ephemeral_keys/{key}
  tags: Ephemeral, Keys, Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/ephemeral-keyskey-delete-openapi.md
- name: Stripe Get Events
  x-api-slug: stripe
  description: List events, going back up to 30 days.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///events
  tags: Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/events-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/events-get-openapi.md
- name: Stripe Get Events
  x-api-slug: stripe
  description: Retrieves the details of an event. Supply the unique identifier of
    the event, which you might have received in a webhook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///events/{id}
  tags: Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/eventsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/eventsid-get-openapi.md
- name: Stripe Add Events  Retry
  x-api-slug: stripe
  description: Resend an event. This only works in testmode
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///events/{id}/retry
  tags: Events, , Retry
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/eventsidretry-post-openapi.md
- name: Stripe Get Exchange Rates
  x-api-slug: stripe
  description: Returns a list of objects that contain the rates at which foreign currencies
    are converted to one another. Only shows the currencies for which Stripe supports.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///exchange_rates
  tags: Exchange, Rates
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/exchange-rates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/exchange-rates-get-openapi.md
- name: Stripe Get Exchange Rates Currency
  x-api-slug: stripe
  description: Retrieves the exchange rates from the given currency to every supported
    currency.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///exchange_rates/{currency}
  tags: Exchange, Rates, Currency
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/exchange-ratescurrency-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/exchange-ratescurrency-get-openapi.md
- name: Stripe Get Invoiceitems
  x-api-slug: stripe
  description: Returns a list of your invoice items. Invoice items are returned sorted
    by creation date, with the most recently created invoice items appearing first.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///invoiceitems
  tags: Invoiceitems
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/invoiceitems-get-openapi.md
- name: Stripe Add Invoiceitems
  x-api-slug: stripe
  description: "Adds an arbitrary charge or credit to the customer\u2019s upcoming
    invoice."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///invoiceitems
  tags: Invoiceitems
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/invoiceitems-post-openapi.md
- name: Stripe Delete Invoiceitems Invoiceitem
  x-api-slug: stripe
  description: "Removes an invoice item from the upcoming invoice. Removing an invoice
    item is only possible before the invoice it\u2019s attached to is closed."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///invoiceitems/{invoiceitem}
  tags: Invoiceitems, Invoiceitem
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/invoiceitemsinvoiceitem-delete-openapi.md
- name: Stripe Get Invoiceitems Invoiceitem
  x-api-slug: stripe
  description: Retrieves the invoice item with the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///invoiceitems/{invoiceitem}
  tags: Invoiceitems, Invoiceitem
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/invoiceitemsinvoiceitem-get-openapi.md
- name: Stripe Add Invoiceitems Invoiceitem
  x-api-slug: stripe
  description: "Updates the amount or description of an invoice item on an upcoming
    invoice. Updating an invoice item is only possible before the invoice it\u2019s
    attached to is closed."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///invoiceitems/{invoiceitem}
  tags: Invoiceitems, Invoiceitem
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/invoiceitemsinvoiceitem-post-openapi.md
- name: Stripe Get Invoices
  x-api-slug: stripe
  description: You can list all invoices, or list the invoices for a specific customer.
    The invoices are returned sorted by creation date, with the most recently created
    invoices appearing first.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///invoices
  tags: Invoices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/invoices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/invoices-get-openapi.md
- name: Stripe Add Invoices
  x-api-slug: stripe
  description: "If you need to invoice your customer outside the regular billing cycle,
    you can create an invoice that pulls in all pending invoice items, including prorations.
    The customer\u2019s billing cycle and regular subscription won\u2019t be affected.Once
    you create the invoice, Stripe will attempt to collect payment according to your
    subscriptions settings, though you can choose to pay it right away."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///invoices
  tags: Invoices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/invoices-post-openapi.md
- name: Stripe Get Invoices Upcoming
  x-api-slug: stripe
  description: "At any time, you can preview the upcoming invoice for a customer.
    This will show you all the charges that are pending, including subscription renewal
    charges, invoice item charges, etc. It will also show you any discount that is
    applicable to the customer.Note that when you are viewing an upcoming invoice,
    you are simply viewing a preview \u2013 the invoice has not yet been created.
    As such, the upcoming invoice will not show up in invoice listing calls, and you
    cannot use the API to pay or edit the invoice. If you want to change the amount
    that your customer will be billed, you can add, remove, or update pending invoice
    items, or update the customer\u2019s discount.You can preview the effects of updating
    a subscription, including a preview of what proration will take place. To ensure
    that the actual proration is calculated exactly the same as the previewed proration,
    you should pass a proration_date parameter when doing the actual subscription
    update. The value passed in should be the same as the subscription_proration_date
    returned on the upcoming invoice resource. The recommended way to get only the
    prorations being previewed is to consider only proration line items where period[start]
    is equal to the subscription_proration_date on the upcoming invoice resource."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///invoices/upcoming
  tags: Invoices, Upcoming
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/invoicesupcoming-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/invoicesupcoming-get-openapi.md
- name: Stripe Get Invoices Invoice
  x-api-slug: stripe
  description: Retrieves the invoice with the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///invoices/{invoice}
  tags: Invoices, Invoice
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/invoicesinvoice-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/invoicesinvoice-get-openapi.md
- name: Stripe Add Invoices Invoice
  x-api-slug: stripe
  description: "Until an invoice is paid, it is marked as open (closed=false). If
    you\u2019d like to stop Stripe from attempting to collect payment on an invoice
    or would simply like to close the invoice out as no longer owed by the customer,
    you can update the closed parameter."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///invoices/{invoice}
  tags: Invoices, Invoice
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/invoicesinvoice-post-openapi.md
- name: Stripe Get Invoices Invoice Lines
  x-api-slug: stripe
  description: "When retrieving an invoice, you\u2019ll get a lines property containing
    the total count of line items and the first handful of those items. There is also
    a URL where you can retrieve the full (paginated) list of line items."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///invoices/{invoice}/lines
  tags: Invoices, Invoice, Lines
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/invoicesinvoicelines-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/invoicesinvoicelines-get-openapi.md
- name: Stripe Add Invoices Invoice Pay
  x-api-slug: stripe
  description: "Stripe automatically creates and then attempts to collect payment
    on invoices for customers on subscriptions according to your subscriptions settings.
    However, if you\u2019d like to attempt payment on an invoice out of the normal
    collection schedule or for some other reason, you can do so."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///invoices/{invoice}/pay
  tags: Invoices, Invoice, Pay
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/invoicesinvoicepay-post-openapi.md
- name: Stripe Get Order Returns
  x-api-slug: stripe
  description: Returns a list of your order returns. The returns are returned sorted
    by creation date, with the most recently created return appearing first.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///order_returns
  tags: Order, Returns
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/order-returns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/order-returns-get-openapi.md
- name: Stripe Get Order Returns
  x-api-slug: stripe
  description: Retrieves the details of an existing order return. Supply the unique
    order ID from either an order return creation request or the order return list,
    and Stripe will return the corresponding order information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///order_returns/{id}
  tags: Order, Returns
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/order-returnsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/order-returnsid-get-openapi.md
- name: Stripe Get Orders
  x-api-slug: stripe
  description: Returns a list of your orders. The orders are returned sorted by creation
    date, with the most recently created orders appearing first.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///orders
  tags: Orders
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/orders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/orders-get-openapi.md
- name: Stripe Add Orders
  x-api-slug: stripe
  description: Post Orders
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///orders
  tags: Orders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/orders-post-openapi.md
- name: Stripe Get Orders
  x-api-slug: stripe
  description: Retrieves the details of an existing order. Supply the unique order
    ID from either an order creation request or the order list, and Stripe will return
    the corresponding order information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///orders/{id}
  tags: Orders
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/ordersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/ordersid-get-openapi.md
- name: Stripe Add Orders
  x-api-slug: stripe
  description: Updates the specific order by setting the values of the parameters
    passed. Any parameters not provided will be left unchanged. This request accepts
    only the metadata, and status as arguments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///orders/{id}
  tags: Orders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/ordersid-post-openapi.md
- name: Stripe Add Orders  Pay
  x-api-slug: stripe
  description: Post Orders, , Pay
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///orders/{id}/pay
  tags: Orders, , Pay
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/ordersidpay-post-openapi.md
- name: Stripe Add Orders  Returns
  x-api-slug: stripe
  description: Return all or part of an order. The order must have a status of paid
    or fulfilled before it can be returned. Once all items have been returned, the
    order will become canceled or returned depending on which status the order started
    in.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///orders/{id}/returns
  tags: Orders, , Returns
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/ordersidreturns-post-openapi.md
- name: Stripe Get Payments
  x-api-slug: stripe
  description: Get Payments
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///payments
  tags: Payments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/payments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/payments-get-openapi.md
- name: Stripe Add Payments
  x-api-slug: stripe
  description: Post Payments
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///payments
  tags: Payments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/payments-post-openapi.md
- name: Stripe Get Payments Payment
  x-api-slug: stripe
  description: Get Payments, Payment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///payments/{payment}
  tags: Payments, Payment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/paymentspayment-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/paymentspayment-get-openapi.md
- name: Stripe Get Payouts
  x-api-slug: stripe
  description: Returns a list of existing payouts sent to third-party bank accounts
    or that Stripe has sent you. The payouts are returned in sorted order, with the
    most recently created payouts appearing first.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///payouts
  tags: Payouts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/payouts-get-openapi.md
- name: Stripe Add Payouts
  x-api-slug: stripe
  description: "To send funds to your own bank account, you create a new payout object.
    Your Stripe balance must be able to cover the payout amount, or you\u2019ll receive
    an \u201CInsufficient Funds\u201D error.If your API key is in test mode, money
    won\u2019t actually be sent, though everything else will occur as if in live mode.If
    you are creating a manual payout on a Stripe account that uses multiple payment
    source types, you\u2019ll need to specify the source type balance that the payout
    should draw from. The balance object details available and pending amounts by
    source type."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///payouts
  tags: Payouts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/payouts-post-openapi.md
- name: Stripe Get Payouts Payout
  x-api-slug: stripe
  description: Retrieves the details of an existing payout. Supply the unique payout
    ID from either a payout creation request or the payout list, and Stripe will return
    the corresponding payout information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///payouts/{payout}
  tags: Payouts, Payout
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/payoutspayout-get-openapi.md
- name: Stripe Add Payouts Payout
  x-api-slug: stripe
  description: Updates the specified payout by setting the values of the parameters
    passed. Any parameters not provided will be left unchanged. This request accepts
    only the metadata as arguments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///payouts/{payout}
  tags: Payouts, Payout
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/payoutspayout-post-openapi.md
- name: Stripe Add Payouts Payout Cancel
  x-api-slug: stripe
  description: A previously created payout can be canceled if it has not yet been
    paid out. Funds will be refunded to your available balance, and the fees you were
    originally charged on the payout will be refunded. You may not cancel automatic
    Stripe payouts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///payouts/{payout}/cancel
  tags: Payouts, Payout, Cancel
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/payoutspayoutcancel-post-openapi.md
- name: Stripe Get Plans
  x-api-slug: stripe
  description: Returns a list of your plans.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///plans
  tags: Plans
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/plans-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/plans-get-openapi.md
- name: Stripe Add Plans
  x-api-slug: stripe
  description: You can create plans using the API, or in the Stripe Dashboard.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///plans
  tags: Plans
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/plans-post-openapi.md
- name: Stripe Delete Plans Plan
  x-api-slug: stripe
  description: "You can delete plans using the API, or in the Stripe Dashboard. Deleting
    plans means new subscribers can\u2019t be added. Existing subscribers aren\u2019t
    affected."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///plans/{plan}
  tags: Plans, Plan
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/plansplan-delete-openapi.md
- name: Stripe Get Plans Plan
  x-api-slug: stripe
  description: Retrieves the plan with the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///plans/{plan}
  tags: Plans, Plan
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/plansplan-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/plansplan-get-openapi.md
- name: Stripe Add Plans Plan
  x-api-slug: stripe
  description: "Updates the specified plan by setting the values of the parameters
    passed. Any parameters not provided are left unchanged. By design, you cannot
    change a plan\u2019s ID, amount, currency, or billing cycle."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///plans/{plan}
  tags: Plans, Plan
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/plansplan-post-openapi.md
- name: Stripe Get Products
  x-api-slug: stripe
  description: Returns a list of your products. The products are returned sorted by
    creation date, with the most recently created products appearing first.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///products
  tags: Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/products-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/products-get-openapi.md
- name: Stripe Add Products
  x-api-slug: stripe
  description: Creates a new product object.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///products
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/products-post-openapi.md
- name: Stripe Delete Products
  x-api-slug: stripe
  description: Delete a product. Deleting a product is only possible if it has no
    SKUs associated with it.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///products/{id}
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/productsid-delete-openapi.md
- name: Stripe Get Products
  x-api-slug: stripe
  description: Retrieves the details of an existing product. Supply the unique product
    ID from either a product creation request or the product list, and Stripe will
    return the corresponding product information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///products/{id}
  tags: Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/productsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/productsid-get-openapi.md
- name: Stripe Add Products
  x-api-slug: stripe
  description: "Updates the specific product by setting the values of the parameters
    passed. Any parameters not provided will be left unchanged.Note that a product\u2019s
    attributes are not editable. Instead, you would need to deactivate the existing
    product and create a new one with the new attribute values."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///products/{id}
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/productsid-post-openapi.md
- name: Stripe Get Recipients
  x-api-slug: stripe
  description: Returns a list of your recipients. The recipients are returned sorted
    by creation date, with the most recently created recipients appearing first.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///recipients
  tags: Recipients
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/recipients-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/recipients-get-openapi.md
- name: Stripe Add Recipients
  x-api-slug: stripe
  description: Post Recipients
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///recipients
  tags: Recipients
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/recipients-post-openapi.md
- name: Stripe Delete Recipients
  x-api-slug: stripe
  description: Permanently deletes a recipient. It cannot be undone.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///recipients/{id}
  tags: Recipients
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/recipientsid-delete-openapi.md
- name: Stripe Get Recipients
  x-api-slug: stripe
  description: Retrieves the details of an existing recipient. You need only supply
    the unique recipient identifier that was returned upon recipient creation.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///recipients/{id}
  tags: Recipients
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/recipientsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/recipientsid-get-openapi.md
- name: Stripe Add Recipients
  x-api-slug: stripe
  description: Post Recipients
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///recipients/{id}
  tags: Recipients
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/recipientsid-post-openapi.md
- name: Stripe Get Refunds
  x-api-slug: stripe
  description: "Returns a list of all refunds you\u2019ve previously created. The
    refunds are returned in sorted order, with the most recent refunds appearing first.
    For convenience, the 10 most recent refunds are always available by default on
    the charge object."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///refunds
  tags: Refunds
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/refunds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/refunds-get-openapi.md
- name: Stripe Add Refunds
  x-api-slug: stripe
  description: Post Refunds
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///refunds
  tags: Refunds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/refunds-post-openapi.md
- name: Stripe Get Refunds Refund
  x-api-slug: stripe
  description: Retrieves the details of an existing refund.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///refunds/{refund}
  tags: Refunds, Refund
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/refundsrefund-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/refundsrefund-get-openapi.md
- name: Stripe Add Refunds Refund
  x-api-slug: stripe
  description: Updates the specified refund by setting the values of the parameters
    passed. Any parameters not provided will be left unchanged.This request only accepts
    metadata as an argument.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///refunds/{refund}
  tags: Refunds, Refund
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/refundsrefund-post-openapi.md
- name: Stripe Get Skus
  x-api-slug: stripe
  description: Returns a list of your SKUs. The SKUs are returned sorted by creation
    date, with the most recently created SKUs appearing first.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///skus
  tags: Skus
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/skus-get-openapi.md
- name: Stripe Add Skus
  x-api-slug: stripe
  description: Creates a new SKU associated with a product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///skus
  tags: Skus
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/skus-post-openapi.md
- name: Stripe Delete Skus
  x-api-slug: stripe
  description: Delete a SKU. Deleting a SKU is only possible until it has been used
    in an order.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///skus/{id}
  tags: Skus
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/skusid-delete-openapi.md
- name: Stripe Get Skus
  x-api-slug: stripe
  description: Retrieves the details of an existing SKU. Supply the unique SKU identifier
    from either a SKU creation request or from the product, and Stripe will return
    the corresponding SKU information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///skus/{id}
  tags: Skus
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/skusid-get-openapi.md
- name: Stripe Add Skus
  x-api-slug: stripe
  description: "Updates the specific SKU by setting the values of the parameters passed.
    Any parameters not provided will be left unchanged.Note that a SKU\u2019s attributes
    are not editable. Instead, you would need to deactivate the existing SKU and create
    a new one with the new attribute values."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///skus/{id}
  tags: Skus
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/skusid-post-openapi.md
- name: Stripe Add Sources
  x-api-slug: stripe
  description: Creates a new source object.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///sources
  tags: Sources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/sources-post-openapi.md
- name: Stripe Get Sources Source
  x-api-slug: stripe
  description: Retrieves an existing source object. Supply the unique source ID from
    a source creation request and Stripe will return the corresponding up-to-date
    source object information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///sources/{source}
  tags: Sources, Source
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/sourcessource-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/sourcessource-get-openapi.md
- name: Stripe Add Sources Source
  x-api-slug: stripe
  description: Updates the specified source by setting the values of the parameters
    passed. Any parameters not provided will be left unchanged.This request accepts
    the metadata and owner as arguments. It is also possible to update type specific
    information for selected payment methods. Please refer to our payment method guides
    for more detail.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///sources/{source}
  tags: Sources, Source
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/sourcessource-post-openapi.md
- name: Stripe Get Sources Source Mandate Notifications Mandate Notification
  x-api-slug: stripe
  description: Get Sources, Source, Mandate, Notifications, Mandate, Notification
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///sources/{source}/mandate_notifications/{mandate_notification}
  tags: Sources, Source, Mandate, Notifications, Mandate, Notification
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/sourcessourcemandate-notificationsmandate-notification-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/sourcessourcemandate-notificationsmandate-notification-get-openapi.md
- name: Stripe Get Sources Source Source Transactions
  x-api-slug: stripe
  description: Get Sources, Source, Source, Transactions
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///sources/{source}/source_transactions
  tags: Sources, Source, Source, Transactions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/sourcessourcesource-transactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/sourcessourcesource-transactions-get-openapi.md
- name: Stripe Get Sources Source Source Transactions Source Transaction
  x-api-slug: stripe
  description: Retrieve an existing source transaction object. Supply the unique source
    ID from a source creation request and the source transaction ID and Stripe will
    return the corresponding up-to-date source object information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///sources/{source}/source_transactions/{source_transaction}
  tags: Sources, Source, Source, Transactions, Source, Transaction
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/sourcessourcesource-transactionssource-transaction-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/sourcessourcesource-transactionssource-transaction-get-openapi.md
- name: Stripe Add Sources Source Verify
  x-api-slug: stripe
  description: Post Sources, Source, Verify
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///sources/{source}/verify
  tags: Sources, Source, Verify
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/sourcessourceverify-post-openapi.md
- name: Stripe Get Subscription Items
  x-api-slug: stripe
  description: Returns a list of your subscription items for a given subscription.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///subscription_items
  tags: Subscription, Items
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/subscription-items-get-openapi.md
- name: Stripe Add Subscription Items
  x-api-slug: stripe
  description: Adds a new item to an existing subscription. No existing items will
    be changed or replaced.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///subscription_items
  tags: Subscription, Items
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/subscription-items-post-openapi.md
- name: Stripe Delete Subscription Items Item
  x-api-slug: stripe
  description: Deletes an item from the subscription. Removing a subscription item
    from a subscription will not cancel the subscription.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///subscription_items/{item}
  tags: Subscription, Items, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/subscription-itemsitem-delete-openapi.md
- name: Stripe Get Subscription Items Item
  x-api-slug: stripe
  description: Retrieves the invoice item with the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///subscription_items/{item}
  tags: Subscription, Items, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/subscription-itemsitem-get-openapi.md
- name: Stripe Add Subscription Items Item
  x-api-slug: stripe
  description: Updates the plan or quantity of an item on a current subscription.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///subscription_items/{item}
  tags: Subscription, Items, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/subscription-itemsitem-post-openapi.md
- name: Stripe Get Subscriptions
  x-api-slug: stripe
  description: By default, returns a list of subscriptions that have not been canceled.
    In order to list canceled subscriptions, specify status=canceled.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///subscriptions
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/subscriptions-get-openapi.md
- name: Stripe Add Subscriptions
  x-api-slug: stripe
  description: Creates a new subscription on an existing customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///subscriptions
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/subscriptions-post-openapi.md
- name: Stripe Delete Subscriptions Subscription Exposed
  x-api-slug: stripe
  description: "Cancels a customer\u2019s subscription. If you set the at_period_end
    parameter to true, the subscription will remain active until the end of the period,
    at which point it will be canceled and not renewed. By default, the subscription
    is terminated immediately. In either case, the customer will not be charged again
    for the subscription. Note, however, that any pending invoice items that you\u2019ve
    created will still be charged for at the end of the period unless manually deleted.
    If you\u2019ve set the subscription to cancel at period end, any pending prorations
    will also be left in place and collected at the end of the period, but if the
    subscription is set to cancel immediately, pending prorations will be removed.By
    default, all unpaid invoices for the customer will be closed upon subscription
    cancellation. We do this in order to prevent unexpected payment attempts once
    the customer has canceled a subscription. However, you can reopen the invoices
    manually after subscription cancellation to have us proceed with payment collection,
    or you could even re-attempt payment yourself on all unpaid invoices before allowing
    the customer to cancel the subscription at all."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///subscriptions/{subscription_exposed_id}
  tags: Subscriptions, Subscription, Exposed
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/subscriptionssubscription-exposed-id-delete-openapi.md
- name: Stripe Get Subscriptions Subscription Exposed
  x-api-slug: stripe
  description: Retrieves the subscription with the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///subscriptions/{subscription_exposed_id}
  tags: Subscriptions, Subscription, Exposed
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/subscriptionssubscription-exposed-id-get-openapi.md
- name: Stripe Add Subscriptions Subscription Exposed
  x-api-slug: stripe
  description: Updates an existing subscription on a customer to match the specified
    parameters. When changing plans or quantities, we will optionally prorate the
    price we charge next month to make up for any price changes. To preview how the
    proration will be calculated, use the upcoming invoice endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///subscriptions/{subscription_exposed_id}
  tags: Subscriptions, Subscription, Exposed
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/subscriptionssubscription-exposed-id-post-openapi.md
- name: Stripe Delete Subscriptions Subscription Exposed  Discount
  x-api-slug: stripe
  description: Delete Subscriptions, Subscription, Exposed, , Discount
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///subscriptions/{subscription_exposed_id}/discount
  tags: Subscriptions, Subscription, Exposed, , Discount
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/subscriptionssubscription-exposed-iddiscount-delete-openapi.md
- name: Stripe Add Tokens
  x-api-slug: stripe
  description: Post Tokens
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///tokens
  tags: Tokens
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/tokens-post-openapi.md
- name: Stripe Get Tokens Token
  x-api-slug: stripe
  description: Retrieves the token with the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///tokens/{token}
  tags: Tokens, Token
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/tokenstoken-get-openapi.md
- name: Stripe Get Transfers
  x-api-slug: stripe
  description: Returns a list of existing transfers sent to connected accounts. The
    transfers are returned in sorted order, with the most recently created transfers
    appearing first.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///transfers
  tags: Transfers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/transfers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/transfers-get-openapi.md
- name: Stripe Add Transfers
  x-api-slug: stripe
  description: Post Transfers
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///transfers
  tags: Transfers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/transfers-post-openapi.md
- name: Stripe Get Transfers  Reversals
  x-api-slug: stripe
  description: You can see a list of the reversals belonging to a specific transfer.
    Note that the 10 most recent reversals are always available by default on the
    transfer object. If you need more than those 10, you can use this API method and
    the limit and starting_after parameters to page through additional reversals.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///transfers/{id}/reversals
  tags: Transfers, , Reversals
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/transfersidreversals-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/transfersidreversals-get-openapi.md
- name: Stripe Add Transfers  Reversals
  x-api-slug: stripe
  description: Post Transfers, , Reversals
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///transfers/{id}/reversals
  tags: Transfers, , Reversals
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/transfersidreversals-post-openapi.md
- name: Stripe Get Transfers Transfer
  x-api-slug: stripe
  description: Retrieves the details of an existing transfer. Supply the unique transfer
    ID from either a transfer creation request or the transfer list, and Stripe will
    return the corresponding transfer information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///transfers/{transfer}
  tags: Transfers, Transfer
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/transferstransfer-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/transferstransfer-get-openapi.md
- name: Stripe Add Transfers Transfer
  x-api-slug: stripe
  description: Post Transfers, Transfer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///transfers/{transfer}
  tags: Transfers, Transfer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/transferstransfer-post-openapi.md
- name: Stripe Get Transfers Transfer Reversals
  x-api-slug: stripe
  description: By default, you can see the 10 most recent reversals stored directly
    on the transfer object, but you can also retrieve details about a specific reversal
    stored on the transfer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///transfers/{transfer}/reversals/{id}
  tags: Transfers, Transfer, Reversals
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/transferstransferreversalsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/transferstransferreversalsid-get-openapi.md
- name: Stripe Add Transfers Transfer Reversals
  x-api-slug: stripe
  description: Updates the specified reversal by setting the values of the parameters
    passed. Any parameters not provided will be left unchanged.This request only accepts
    metadata and description as arguments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///transfers/{transfer}/reversals/{id}
  tags: Transfers, Transfer, Reversals
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/transferstransferreversalsid-post-openapi.md
- name: Stripe
  x-api-slug: stripe
  description: Web and mobile payments, built for developers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Stripe
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stripe/master/_listings/stripe/openapi.md
x-common:
- type: x-base
  url: https://api.stripe.com/
- type: x-blog
  url: https://stripe.com/blog
- type: x-blog-rss
  url: https://stripe.com/blog/feed.rss
- type: x-change-log
  url: https://stripe.com/docs/upgrades
- type: x-crunchbase
  url: http://www.crunchbase.com/company/stripe
- type: x-crunchbase
  url: https://crunchbase.com/organization/stripe
- type: x-email
  url: info@stripe.com
- type: x-email
  url: privacy@stripe.com
- type: x-email
  url: atlas@stripe.com
- type: x-email
  url: notices@stripe.com
- type: x-email
  url: jane.diaz@stripe.com
- type: x-email
  url: nonprofit@stripe.com
- type: x-email
  url: support@stripe.com
- type: x-email
  url: dpo@stripe.com
- type: x-github
  url: https://github.com/stripe
- type: x-linkedin
  url: https://www.linkedin.com/company/stripe/
- type: x-pricing
  url: https://stripe.com/us/pricing
- type: x-twitter
  url: https://twitter.com/stripe
- type: x-website
  url: https://stripe.com/
- type: x-website
  url: http://stripe.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---