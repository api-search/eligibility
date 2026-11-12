---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is provided for business and professional use only, not for personal, family, or household purposes.
    type: business
  - text: You must be at least 18 years old and legally able to enter into a contract to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into a contract to use the Service.
    value: '18'
  restricted_uses:
  - summary: Regulated advice without licence
    text: use the Service to provide regulated advice (including financial, medical, legal, or therapeutic advice) where you are not licensed and authorized to do so
  - summary: Political campaigning
    text: use the Service for political campaigning, electioneering, or coordinated inauthentic behavior
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
name: Cloziq
provenance_date: '2026-11-09'
provider_name: Cloziq
provider_slug: cloziq-com
slug: cloziq-com-eligibility
source_date: '2026-11-09'
source_filename: cloziq-com-eligibility.yml
source_heading: Eligibility
source_page: https://cloziq.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cloziq\naid: cloziq-com\nurl: https://cloziq.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is provided for business and professional use only, not for personal, family, or household purposes.\n- type: individual\n  text: You must be at least 18 years old and legally able to enter into a contract to use the Service.\nrestricted_uses:\n- summary: Regulated advice without licence\n  text: use the Service to provide regulated advice (including financial, medical, legal, or therapeutic advice)\n  \
  \  where you are not licensed and authorized to do so\n- summary: Political campaigning\n  text: use the Service for political campaigning, electioneering, or coordinated inauthentic behavior\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into a contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/cloziq-com/eligibility/cloziq-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Cloziq's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Sales Agent
- Instagram
- Facebook Messenger
- Direct Messaging
- Appointment Setting
- Sales Automation
- Model Context Protocol
---
