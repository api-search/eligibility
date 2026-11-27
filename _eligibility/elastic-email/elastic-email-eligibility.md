---
api_specs:
- filename: elastic-email-elastic-email-api-api-openapi.yml
  format: yaml
  label: Elastic Email Elastic Email API
  slug: elastic-email-elastic-email-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elastic-email/openapi/elastic-email-elastic-email-api-api-openapi.yml
- filename: elastic-email-emails-api-openapi.yml
  format: yaml
  label: Elastic Email Emails API
  slug: elastic-email-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elastic-email/openapi/elastic-email-emails-api-openapi.yml
- filename: elastic-email-hooks-api-openapi.yml
  format: yaml
  label: Elastic Email Hooks API
  slug: elastic-email-hooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elastic-email/openapi/elastic-email-hooks-api-openapi.yml
- filename: elastic-email-webhook-api-openapi.yml
  format: yaml
  label: Elastic Email Webhook API
  slug: elastic-email-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/elastic-email/openapi/elastic-email-webhook-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing or using the Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to these Terms.
    type: business
  minimum_age:
    text: be at least the age of majority in your jurisdiction
    value: age of majority in your jurisdiction
  restricted_uses:
  - summary: Bulk or unsolicited sending
    text: You must not send Transactional Messages that are bulk messages
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Elastic Email
provenance_date: '2026-11-09'
provider_name: Elastic Email
provider_slug: elastic-email
slug: elastic-email-eligibility
source_date: '2026-11-09'
source_filename: elastic-email-eligibility.yml
source_heading: Eligibility
source_page: https://elasticemail.com/resources/usage-policies/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Elastic Email\naid: elastic-email\nurl: https://elasticemail.com/resources/usage-policies/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing or using the Services on behalf of a company (such as your employer) or other legal\n    entity, you represent and warrant that you have the authority to bind that company or other legal entity to\n    these Terms.\nrestricted_uses:\n- summary: Bulk or unsolicited sending\n  text: You must not send Transactional Messages that are bulk messages\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority in your jurisdiction\n  text: be at least the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/elastic-email/eligibility/elastic-email-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Elastic Email's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email
- Marketing
- Software-as-a-Service
---
