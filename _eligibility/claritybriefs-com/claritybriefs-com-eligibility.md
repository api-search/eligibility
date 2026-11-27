---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years of age to use the Service.
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 16 years of age to use the Service.
    value: '16'
  restricted_uses:
  - summary: Content guidelines
    text: Promotes violence, discrimination, or illegal activities
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
name: claritybriefs-com
provenance_date: '2026-11-09'
provider_name: claritybriefs-com
provider_slug: claritybriefs-com
slug: claritybriefs-com-eligibility
source_date: '2026-11-09'
source_filename: claritybriefs-com-eligibility.yml
source_heading: Eligibility
source_page: https://claritybriefs.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: claritybriefs-com\naid: claritybriefs-com\nurl: https://claritybriefs.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years of age to use the Service.\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have the authority to\n    bind that organization to these Terms.\nrestricted_uses:\n- summary: Content guidelines\n  text: Promotes violence, discrimination, or illegal activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/claritybriefs-com/eligibility/claritybriefs-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from claritybriefs-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
