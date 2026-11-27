---
claim_count: 8
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: The Services are intended for users who are at least 18 years old.
    type: individual
  - text: whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Regulated data (HIPAA, FISMA, etc.)
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
  - summary: Gramm-Leach-Bliley Act use
    text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
  - summary: Automated access by bots or scripts
    text: you will not access the Services through automated or non-human means, whether through a bot, script or otherwise
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register to use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Crash Override
provenance_date: '2026-11-09'
provider_name: Crash Override
provider_slug: crash-override
slug: crash-override-eligibility
source_date: '2026-11-09'
source_filename: crash-override-eligibility.yml
source_heading: Eligibility
source_page: https://crashoverride.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Crash Override\naid: crash-override\nurl: https://crashoverride.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: The Services are intended for users who are at least 18 years old.\n- type: business\n  text: whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Regulated data (HIPAA, FISMA,\
  \ etc.)\n  text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\n- summary: Gramm-Leach-Bliley Act use\n  text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\n- summary: Automated access by bots or scripts\n  text: you will not access the Services through automated or non-human means, whether through a bot, script or\n    otherwise\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register to use the Services.\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/crash-override/eligibility/crash-override-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 8 quoted statements, read from Crash Override's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Software Supply Chain
- Application Security
- Provenance
- DevSecOps
- Open Source
- Artifact Tracking
---
