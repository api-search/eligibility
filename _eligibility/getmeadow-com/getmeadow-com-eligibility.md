---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Meadow is solely for qualified patients or adult-use customers residing in states that have adopted legislation providing legal medical or adult-use cannabis retail.
  entity_types:
  - text: By using the Application or Service, you represent and warrant that you are at least 18 years old.
    type: individual
  - text: Be legally organized and operating in Compliance with the laws of your State;
    type: business
  minimum_age:
    text: In all events, the Service and Application are not available to persons under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: You will only use the Service or Application for lawful purposes;
  - summary: Adult-use or qualified patient use only
    text: You will at all times use the Service SOLELY as an adult-use customer or qualified medical cannabis patient and/or, where permitted by applicable law, as a primary caregiver for such a qualified patient.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You will provide us with whatever proof of identity we may reasonably request.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Meadow
provenance_date: '2026-11-09'
provider_name: Meadow
provider_slug: getmeadow-com
slug: getmeadow-com-eligibility
source_date: '2026-11-09'
source_filename: getmeadow-com-eligibility.yml
source_heading: Eligibility
source_page: https://getmeadow.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Meadow\naid: getmeadow-com\nurl: https://getmeadow.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Meadow is solely for qualified patients or adult-use customers residing in states that have adopted legislation\n    providing legal medical or adult-use cannabis retail.\nentity_types:\n- type: individual\n  text: By using the Application or Service, you represent and warrant that you are at least 18 years old.\n- type: business\n  text: Be legally organized and operating in Compliance with the laws of your State;\nrestricted_uses:\n- summary: Lawful use\
  \ only\n  text: You will only use the Service or Application for lawful purposes;\n- summary: Adult-use or qualified patient use only\n  text: You will at all times use the Service SOLELY as an adult-use customer or qualified medical cannabis patient\n    and/or, where permitted by applicable law, as a primary caregiver for such a qualified patient.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You will provide us with whatever proof of identity we may reasonably request.\nminimum_age:\n  value: '18'\n  text: In all events, the Service and Application are not available to persons under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/getmeadow-com/eligibility/getmeadow-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Meadow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cannabis
- Point-of-Sale
- E-Commerce
- Software-as-a-Service
---
