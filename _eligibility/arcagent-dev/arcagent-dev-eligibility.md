---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the service if you are suspended, barred by applicable law, or using ArcAgent for a sanctioned person, entity, or jurisdiction.
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract to use ArcAgent.
    type: individual
  - text: If you use ArcAgent on behalf of a company or other entity, you represent that you have authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract to use ArcAgent.
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons or jurisdictions
    text: using ArcAgent for a sanctioned person, entity, or jurisdiction
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
name: ArcAgent
provenance_date: '2026-11-09'
provider_name: ArcAgent
provider_slug: arcagent-dev
slug: arcagent-dev-eligibility
source_date: '2026-11-09'
source_filename: arcagent-dev-eligibility.yml
source_heading: Eligibility
source_page: https://www.arcagent.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ArcAgent\naid: arcagent-dev\nurl: https://www.arcagent.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the service if you are suspended, barred by applicable law, or using ArcAgent for a sanctioned\n    person, entity, or jurisdiction.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract to use ArcAgent.\n- type: business\n  text: If you use ArcAgent on behalf of a company or other entity, you represent that you have authority to bind\n    that entity to these Terms.\nrestricted_uses:\n- summary:\
  \ Sanctioned persons or jurisdictions\n  text: using ArcAgent for a sanctioned person, entity, or jurisdiction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract to use ArcAgent.\n"
source_yaml_url: https://artifacts.apis.io/arcagent-dev/eligibility/arcagent-dev-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from ArcAgent's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Bounties
- Software Development
- Outsourcing
- Automation
---
