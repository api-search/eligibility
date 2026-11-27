---
api_specs:
- filename: sendlane-automations-api-openapi.yml
  format: yaml
  label: Sendlane Automations API
  slug: sendlane-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendlane/openapi/sendlane-automations-api-openapi.yml
- filename: sendlane-campaigns-api-openapi.yml
  format: yaml
  label: Sendlane Campaigns API
  slug: sendlane-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendlane/openapi/sendlane-campaigns-api-openapi.yml
- filename: sendlane-contacts-api-openapi.yml
  format: yaml
  label: Sendlane Contacts API
  slug: sendlane-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendlane/openapi/sendlane-contacts-api-openapi.yml
- filename: sendlane-custom-fields-api-openapi.yml
  format: yaml
  label: Sendlane Custom Fields API
  slug: sendlane-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendlane/openapi/sendlane-custom-fields-api-openapi.yml
- filename: sendlane-custom-integration-events-api-openapi.yml
  format: yaml
  label: Sendlane Custom Integration Events API
  slug: sendlane-custom-integration-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendlane/openapi/sendlane-custom-integration-events-api-openapi.yml
- filename: sendlane-custom-integration-webhooks-api-openapi.yml
  format: yaml
  label: Sendlane Custom Integration Webhooks API
  slug: sendlane-custom-integration-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendlane/openapi/sendlane-custom-integration-webhooks-api-openapi.yml
- filename: sendlane-custom-integrations-api-openapi.yml
  format: yaml
  label: Sendlane Custom Integrations API
  slug: sendlane-custom-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendlane/openapi/sendlane-custom-integrations-api-openapi.yml
- filename: sendlane-list-contacts-api-openapi.yml
  format: yaml
  label: Sendlane List Contacts API
  slug: sendlane-list-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendlane/openapi/sendlane-list-contacts-api-openapi.yml
- filename: sendlane-lists-api-openapi.yml
  format: yaml
  label: Sendlane Lists API
  slug: sendlane-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendlane/openapi/sendlane-lists-api-openapi.yml
- filename: sendlane-segments-api-openapi.yml
  format: yaml
  label: Sendlane Segments API
  slug: sendlane-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendlane/openapi/sendlane-segments-api-openapi.yml
- filename: sendlane-senders-api-openapi.yml
  format: yaml
  label: Sendlane Senders API
  slug: sendlane-senders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendlane/openapi/sendlane-senders-api-openapi.yml
- filename: sendlane-sms-api-openapi.yml
  format: yaml
  label: Sendlane SMS API
  slug: sendlane-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendlane/openapi/sendlane-sms-api-openapi.yml
- filename: sendlane-suppression-api-openapi.yml
  format: yaml
  label: Sendlane Suppression API
  slug: sendlane-suppression-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendlane/openapi/sendlane-suppression-api-openapi.yml
- filename: sendlane-tags-api-openapi.yml
  format: yaml
  label: Sendlane Tags API
  slug: sendlane-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendlane/openapi/sendlane-tags-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission to use the Services
    value: legal age
  restricted_uses:
  - summary: Restricted business types
    text: businesses offering the following types of services, products, or content cannot utilize our Services
  - summary: Gambling and pharmaceutical products
    text: (b) pharmaceutical products; (c) work from home (i.e. surveys from home, jobs from home), business opportunities, get rich quick schemes, or any highly unachievable results; ‍ (d) online trading, day trading tips, or stock market-related Content; (e) gambling services or products;
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
name: Sendlane
provenance_date: '2026-11-10'
provider_name: Sendlane
provider_slug: sendlane
slug: sendlane-eligibility
source_date: '2026-11-10'
source_filename: sendlane-eligibility.yml
source_heading: Eligibility
source_page: https://www.sendlane.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sendlane\naid: sendlane\nurl: https://www.sendlane.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or entity’s behalf\nrestricted_uses:\n- summary: Restricted business types\n  text: businesses offering the following types of services,\
  \ products, or content cannot utilize our Services\n- summary: Gambling and pharmaceutical products\n  text: (b) pharmaceutical products; (c) work from home (i.e. surveys from home, jobs from home), business opportunities,\n    get rich quick schemes, or any highly unachievable results; ‍ (d) online trading, day trading tips, or stock\n    market-related Content; (e) gambling services or products;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Services\n"
source_yaml_url: https://artifacts.apis.io/sendlane/eligibility/sendlane-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Sendlane's own page on 2026-11-10.
synthetic: false
tags:
- Email Marketing
- SMS Marketing
- E-Commerce
- Marketing Automation
- Contacts
- Campaigns
- Segmentation
- Consent Management
- Suppression
- Event Tracking
- Revenue Attribution
---
