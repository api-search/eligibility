---
api_specs:
- filename: holvi-account-information-api-openapi.yml
  format: yaml
  label: Holvi Account Information API
  slug: holvi-account-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/holvi/openapi/holvi-account-information-api-openapi.yml
- filename: holvi-consent-api-openapi.yml
  format: yaml
  label: Holvi Consent API
  slug: holvi-consent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/holvi/openapi/holvi-consent-api-openapi.yml
- filename: holvi-payment-initiation-api-openapi.yml
  format: yaml
  label: Holvi Payment Initiation API
  slug: holvi-payment-initiation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/holvi/openapi/holvi-payment-initiation-api-openapi.yml
- filename: holvi-third-party-provider-api-openapi.yml
  format: yaml
  label: Holvi Third Party Provider API
  slug: holvi-third-party-provider-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/holvi/openapi/holvi-third-party-provider-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - DE
    text: All Customers that register for and open a Holvi business account in Germany will be served by Holvi Payment Services Oy Zweigniederlassung - Deutschland.
  entity_types:
  - text: Holvi provides its services exclusively to corporate clients, not consumers.
    type: business
  - text: The User or the Customer (if it is a natural person) must be at least 18 years of age and domiciled in a Member State of the European Union or European Economic Area where Holvi Service is available
    type: individual
  minimum_age:
    text: must be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Business purposes only
    text: The Payment Account is offered only for business purposes and by accepting these Terms of Service you confirm as a Customer that you are a business person using the Payment Account for business purposes.
  verification:
    approval_required: true
    kyb: true
    kyc: true
    text: the examination of the details of the Customer's business, including the beneficial owners, in accordance with the requirements of applicable anti-money laundering (AML) regulation, and the application has been approved by Holvi.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Holvi
provenance_date: '2026-11-09'
provider_name: Holvi
provider_slug: holvi
slug: holvi-eligibility
source_date: '2026-11-09'
source_filename: holvi-eligibility.yml
source_heading: Eligibility
source_page: https://support.holvi.com/hc/en-gb/articles/33569262656402-Terms-of-Service-until-28-09-2026
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Holvi\naid: holvi\nurl: https://support.holvi.com/hc/en-gb/articles/33569262656402-Terms-of-Service-until-28-09-2026\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - DE\n  excluded: []\n  text: All Customers that register for and open a Holvi business account in Germany will be served by Holvi Payment\n    Services Oy Zweigniederlassung - Deutschland.\nentity_types:\n- type: business\n  text: Holvi provides its services exclusively to corporate clients, not consumers.\n- type: individual\n  text: The User or the Customer (if it is a natural person) must be at least 18 years of age and\
  \ domiciled in a\n    Member State of the European Union or European Economic Area where Holvi Service is available\nrestricted_uses:\n- summary: Business purposes only\n  text: The Payment Account is offered only for business purposes and by accepting these Terms of Service you confirm\n    as a Customer that you are a business person using the Payment Account for business purposes.\nverification:\n  kyc: true\n  kyb: true\n  approval_required: true\n  text: the examination of the details of the Customer's business, including the beneficial owners, in accordance\n    with the requirements of applicable anti-money laundering (AML) regulation, and the application has been approved\n    by Holvi.\nminimum_age:\n  value: '18'\n  text: must be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/holvi/eligibility/holvi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Holvi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Banking
- Fintech
- Payments
- Business Banking
- PSD2
- Open Banking
- SEPA
- Finland
---
