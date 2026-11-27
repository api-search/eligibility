---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: The App and website including AI features and telemedicine services, and products sold on app are not available for users outside India. Select products are available for purchase outside India through marketplaces in a few countries.
  entity_types:
  - text: Use of the Website is available only to persons who can form legally binding contracts under applicable law.
    type: individual
  - text: If you are registering as a business entity, You represent that You have the authority to bind the entity to this User Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Emergency medical needs
    text: Do not use this App or any of our Services for emergency medical needs.
  - summary: Treating medical emergencies or diagnosis
    text: The site is not intended to diagnose a medical condition.
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
name: Cureskin
provenance_date: '2026-11-09'
provider_name: Cureskin
provider_slug: cureskin
slug: cureskin-eligibility
source_date: '2026-11-09'
source_filename: cureskin-eligibility.yml
source_heading: Eligibility
source_page: https://cureskin.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cureskin\naid: cureskin\nurl: https://cureskin.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: The App and website including AI features and telemedicine services, and products sold on app are not available\n    for users outside India. Select products are available for purchase outside India through marketplaces in a\n    few countries.\nentity_types:\n- type: individual\n  text: Use of the Website is available only to persons who can form legally binding contracts under applicable\n    law.\n- type: business\n  text: If you are registering as a business\
  \ entity, You represent that You have the authority to bind the entity\n    to this User Agreement.\nrestricted_uses:\n- summary: Emergency medical needs\n  text: Do not use this App or any of our Services for emergency medical needs.\n- summary: Treating medical emergencies or diagnosis\n  text: The site is not intended to diagnose a medical condition.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cureskin/eligibility/cureskin-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Cureskin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Dermatology
- Skincare
- Hair Care
---
