---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'To use the Platform, you must: be at least 18 years old or the age of majority in your jurisdiction, whichever is higher; have legal capacity to enter into binding agreements'
    type: individual
  - text: If you use the Platform on behalf of a company, organization, family member, or other person, you represent and warrant that you have authority to bind that person or entity to these Terms.
    type: business
  minimum_age:
    text: be at least 18 years old or the age of majority in your jurisdiction, whichever is higher
    value: '18'
  restricted_uses:
  - summary: Unlawful, fraudulent or harmful use
    text: use the Platform unlawfully or fraudulently
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
name: Cloudofgoods
provenance_date: '2026-11-09'
provider_name: Cloudofgoods
provider_slug: cloudofgoods
slug: cloudofgoods-eligibility
source_date: '2026-11-09'
source_filename: cloudofgoods-eligibility.yml
source_heading: Eligibility
source_page: https://www.cloudofgoods.com/terms_of_use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cloudofgoods\naid: cloudofgoods\nurl: https://www.cloudofgoods.com/terms_of_use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'To use the Platform, you must: be at least 18 years old or the age of majority in your jurisdiction, whichever\n    is higher; have legal capacity to enter into binding agreements'\n- type: business\n  text: If you use the Platform on behalf of a company, organization, family member, or other person, you represent\n    and warrant that you have authority to bind that person or entity to these Terms.\nrestricted_uses:\n\
  - summary: Unlawful, fraudulent or harmful use\n  text: use the Platform unlawfully or fraudulently\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: be at least 18 years old or the age of majority in your jurisdiction, whichever is higher\n"
source_yaml_url: https://artifacts.apis.io/cloudofgoods/eligibility/cloudofgoods-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cloudofgoods's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Rentals
- Marketplace
- Travel
- Equipment
---
