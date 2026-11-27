---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least the age of majority in your jurisdiction or have consent from a parent or guardian in order to access and use the Services
    type: individual
  - text: IF YOU ARE USING THE SERVICES ON BEHALF OF AN ORGANIZATION, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND THE ORGANIZATION TO THE TERMS
    type: business
  minimum_age:
    text: You must be at least the age of majority in your jurisdiction or have consent from a parent or guardian in order to access and use the Services
    value: age of majority
  restricted_uses:
  - summary: Harmful content
    text: conduct in a manner, upload or generate content that may directly or indirectly cause harm to yourself or others while using the Services including but not limited to weapon development, military, warfare, destruction of critical infrastructure, self-harm and eating disorders;
  - summary: Economic harm uses
    text: automated determinations of eligibility for credit, employment, educational institutions or public assistance services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'Klarify may collect a variety of personal verification information from you, including but not limited to your: email address; name; date of birth; payment information'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Klarify
provenance_date: '2026-11-09'
provider_name: Klarify
provider_slug: klarify
slug: klarify-eligibility
source_date: '2026-11-09'
source_filename: klarify-eligibility.yml
source_heading: Eligibility
source_page: https://www.klarify.ca/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Klarify\naid: klarify\nurl: https://www.klarify.ca/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least the age of majority in your jurisdiction or have consent from a parent or guardian\n    in order to access and use the Services\n- type: business\n  text: IF YOU ARE USING THE SERVICES ON BEHALF OF AN ORGANIZATION, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO\n    BIND THE ORGANIZATION TO THE TERMS\nrestricted_uses:\n- summary: Harmful content\n  text: conduct in a manner, upload or generate\
  \ content that may directly or indirectly cause harm to yourself or\n    others while using the Services including but not limited to weapon development, military, warfare, destruction\n    of critical infrastructure, self-harm and eating disorders;\n- summary: Economic harm uses\n  text: automated determinations of eligibility for credit, employment, educational institutions or public assistance\n    services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'Klarify may collect a variety of personal verification information from you, including but not limited\n    to your: email address; name; date of birth; payment information'\nminimum_age:\n  value: age of majority\n  text: You must be at least the age of majority in your jurisdiction or have consent from a parent or guardian\n    in order to access and use the Services\n"
source_yaml_url: https://artifacts.apis.io/klarify/eligibility/klarify-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Klarify's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Mental Health
- Artificial Intelligence
- Clinical Documentation
- Medical Records
- Insurance
- Practice Management
- Vertical SaaS
- Directory
---
