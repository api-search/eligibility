---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Products and Services are not available to all persons or in all countries; OFAC Specially Designated Nationals and OFAC sanctioned countries are prohibited.
  entity_types:
  - text: Only individuals age 18+ who can form a binding contract with Conservation Labs are permitted to subscribe to or register for Subscription Services or be an End User.
    type: individual
  - text: If the individual indicating assent to the Agreement is doing so on behalf of an organization, all references to “you” or “your” in these Terms shall mean the legal entity represented by such individual.
    type: business
  minimum_age:
    text: Only individuals age 18+ who can form a binding contract with Conservation Labs are permitted to subscribe to or register for Subscription Services or be an End User.
    value: '18'
  restricted_uses:
  - summary: Not for life-safety or critical uses
    text: YOU AGREE THAT YOU WILL NOT RELY ON THE SERVICES FOR ANY LIFE SAFETY OR CRITICAL PURPOSES OR PROTECTION OF PROPERTY.
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
name: Conservation Labs
provenance_date: '2026-11-09'
provider_name: Conservation Labs
provider_slug: conservation-labs
slug: conservation-labs-eligibility
source_date: '2026-11-09'
source_filename: conservation-labs-eligibility.yml
source_heading: Eligibility
source_page: https://conservationlabs.com/index.php/knowledge-base/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Conservation Labs\naid: conservation-labs\nurl: https://conservationlabs.com/index.php/knowledge-base/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Products and Services are not available to all persons or in all countries; OFAC Specially Designated Nationals\n    and OFAC sanctioned countries are prohibited.\nentity_types:\n- type: individual\n  text: Only individuals age 18+ who can form a binding contract with Conservation Labs are permitted to subscribe\n    to or register for Subscription Services or be an End User.\n- type: business\n\
  \  text: If the individual indicating assent to the Agreement is doing so on behalf of an organization, all references\n    to “you” or “your” in these Terms shall mean the legal entity represented by such individual.\nrestricted_uses:\n- summary: Not for life-safety or critical uses\n  text: YOU AGREE THAT YOU WILL NOT RELY ON THE SERVICES FOR ANY LIFE SAFETY OR CRITICAL PURPOSES OR PROTECTION\n    OF PROPERTY.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Only individuals age 18+ who can form a binding contract with Conservation Labs are permitted to subscribe\n    to or register for Subscription Services or be an End User.\n"
source_yaml_url: https://artifacts.apis.io/conservation-labs/eligibility/conservation-labs-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Conservation Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Water
- IoT
- Smart Home
- Sustainability
- Leak Detection
- Sensors
- Predictive Maintenance
---
