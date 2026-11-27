---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use the Service. By using the Service, you represent and warrant that you are at least 18 years old and have the legal capacity to enter into these Terms of Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use the Service.
    value: '18'
  restricted_uses:
  - summary: Resale of products
    text: or resell any contact lenses, glasses, or other products you obtain through the Service, unless you are a medical professional licensed to do so.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Before we ship any contact lenses to you, we are required to either review a copy of your current prescription or contact your medical professional regarding the prescription information you provide to us.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hubble Contacts
provenance_date: '2026-11-09'
provider_name: Hubble Contacts
provider_slug: hubble-contacts
slug: hubble-contacts-eligibility
source_date: '2026-11-09'
source_filename: hubble-contacts-eligibility.yml
source_heading: Eligibility
source_page: https://tos.hubblecontacts.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hubble Contacts\naid: hubble-contacts\nurl: https://tos.hubblecontacts.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Service. By using the Service, you represent and warrant\n    that you are at least 18 years old and have the legal capacity to enter into these Terms of Service.\nrestricted_uses:\n- summary: Resale of products\n  text: or resell any contact lenses, glasses, or other products you obtain through the Service, unless you are\n    a medical professional\
  \ licensed to do so.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Before we ship any contact lenses to you, we are required to either review a copy of your current prescription\n    or contact your medical professional regarding the prescription information you provide to us.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/hubble-contacts/eligibility/hubble-contacts-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Hubble Contacts's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Retail
- Health
- Vision Care
- Contact Lenses
- Subscription
- Agentic Commerce
- MCP
- Shopify
- GraphQL
---
