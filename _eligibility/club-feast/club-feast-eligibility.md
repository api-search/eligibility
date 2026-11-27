---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Club Feast may not be downloaded outside of the United States.
  entity_types:
  - text: Club Feast does serve corporate accounts, non profits, and other organizations.
    type: business
  - text: Club Feast does serve corporate accounts, non profits, and other organizations.
    type: nonprofit
  - text: If you are an individual accessing Club Feast on behalf of a corporation, you agree and warrant that you have the authority to bind the company or organization you represent to these terms
    type: individual
  minimum_age:
    text: not to use Club Feast or its services or submit content to Club Feast if you are under the age of 18;
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: not to use Club Feast for illegal purposes;
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Food preparation services or restaurants may become a "Restaurant Partners" ("RP") through the approval of Club Feast, Inc.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Club Feast
provenance_date: '2026-11-09'
provider_name: Club Feast
provider_slug: club-feast
slug: club-feast-eligibility
source_date: '2026-11-09'
source_filename: club-feast-eligibility.yml
source_heading: Eligibility
source_page: https://app.clubfeast.com/legal/terms_of_service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Club Feast\naid: club-feast\nurl: https://app.clubfeast.com/legal/terms_of_service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Club Feast may not be downloaded outside of the United States.\nentity_types:\n- type: business\n  text: Club Feast does serve corporate accounts, non profits, and other organizations.\n- type: nonprofit\n  text: Club Feast does serve corporate accounts, non profits, and other organizations.\n- type: individual\n  text: If you are an individual accessing Club Feast on behalf of a corporation, you agree and warrant that you\n    have the authority\
  \ to bind the company or organization you represent to these terms\nrestricted_uses:\n- summary: Illegal purposes\n  text: not to use Club Feast for illegal purposes;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Food preparation services or restaurants may become a \"Restaurant Partners\" (\"RP\") through the approval\n    of Club Feast, Inc.\nminimum_age:\n  value: '18'\n  text: not to use Club Feast or its services or submit content to Club Feast if you are under the age of 18;\n"
source_yaml_url: https://artifacts.apis.io/club-feast/eligibility/club-feast-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Club Feast's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food Delivery
- Corporate Catering
- Restaurant
- Logistics
- Meal Subscription
- Office Pantry
---
