---
api_specs:
- filename: persistiq-campaigns-api-openapi.yml
  format: yaml
  label: PersistIQ Campaigns API
  slug: persistiq-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-campaigns-api-openapi.yml
- filename: persistiq-do-not-contact-domains-api-openapi.yml
  format: yaml
  label: PersistIQ Do Not Contact Domains API
  slug: persistiq-do-not-contact-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-do-not-contact-domains-api-openapi.yml
- filename: persistiq-events-api-openapi.yml
  format: yaml
  label: PersistIQ Events API
  slug: persistiq-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-events-api-openapi.yml
- filename: persistiq-lead-fields-api-openapi.yml
  format: yaml
  label: PersistIQ Lead Fields API
  slug: persistiq-lead-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-lead-fields-api-openapi.yml
- filename: persistiq-lead-statuses-api-openapi.yml
  format: yaml
  label: PersistIQ Lead Statuses API
  slug: persistiq-lead-statuses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-lead-statuses-api-openapi.yml
- filename: persistiq-leads-api-openapi.yml
  format: yaml
  label: PersistIQ Leads API
  slug: persistiq-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-leads-api-openapi.yml
- filename: persistiq-users-api-openapi.yml
  format: yaml
  label: PersistIQ Users API
  slug: persistiq-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-users-api-openapi.yml
- filename: persistiq-campaign-leads-api-openapi.yml
  format: yaml
  label: PersistIQ Campaign Leads API
  slug: persistiq-campaign-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-campaign-leads-api-openapi.yml
- filename: persistiq-dnc-domains-api-openapi.yml
  format: yaml
  label: PersistIQ DNC Domains API
  slug: persistiq-dnc-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-dnc-domains-api-openapi.yml
- filename: persistiq-replies-api-openapi.yml
  format: yaml
  label: PersistIQ Replies API
  slug: persistiq-replies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-replies-api-openapi.yml
- filename: persistiq-tags-api-openapi.yml
  format: yaml
  label: PersistIQ Tags API
  slug: persistiq-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-tags-api-openapi.yml
- filename: persistiq-webhook-plugin-api-openapi.yml
  format: yaml
  label: PersistIQ Webhook Plugin API
  slug: persistiq-webhook-plugin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persistiq/openapi/persistiq-webhook-plugin-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an individual subscriber, customer, member, or user having attained the age of majority
    type: individual
  - text: a single company, organization, or entity
    type: business
  minimum_age:
    text: The Service is not available to persons under the age of majority or to any Users previously suspended or removed from the Service by Company.
    value: age of majority
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
name: PersistIQ
provenance_date: '2026-11-10'
provider_name: PersistIQ
provider_slug: persistiq
slug: persistiq-eligibility
source_date: '2026-11-10'
source_filename: persistiq-eligibility.yml
source_heading: Eligibility
source_page: https://www.persistiq.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PersistIQ\naid: persistiq\nurl: https://www.persistiq.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: an individual subscriber, customer, member, or user having attained the age of majority\n- type: business\n  text: a single company, organization, or entity\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: The Service is not available to persons under the age of majority or to any Users previously suspended or\n\
  \    removed from the Service by Company.\n"
source_yaml_url: https://artifacts.apis.io/persistiq/eligibility/persistiq-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from PersistIQ's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sales Engagement
- Sales
- Outbound
- Email Outreach
- CRM
- Lead Management
- Marketing
- Webhook
- SEP
---
