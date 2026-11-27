---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You shall not use the Service in any country or territory that is subject to a U.S. government embargo or sanctions.
  entity_types:
  - text: You are at least 18 years of age or the legal age of majority in your jurisdiction.
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent and warrant that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You are at least 18 years of age or the legal age of majority in your jurisdiction.
    value: '18'
  restricted_uses:
  - summary: Safety-critical applications
    text: You shall not use the Service as the sole computational authority for any application where computational errors could result in death, personal injury, property damage, environmental harm, or significant financial loss
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Service, you must create an account by providing a valid email address and explicitly accepting these Terms.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Arithym
provenance_date: '2026-11-09'
provider_name: Arithym
provider_slug: arithym-xyz
slug: arithym-xyz-eligibility
source_date: '2026-11-09'
source_filename: arithym-xyz-eligibility.yml
source_heading: Eligibility
source_page: https://arithym.xyz/legal/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arithym\naid: arithym-xyz\nurl: https://arithym.xyz/legal/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You shall not use the Service in any country or territory that is subject to a U.S. government embargo or\n    sanctions.\nentity_types:\n- type: individual\n  text: You are at least 18 years of age or the legal age of majority in your jurisdiction.\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent and warrant that you have authority\n    to bind that organization to these Terms.\nrestricted_uses:\n- summary: Safety-critical\
  \ applications\n  text: You shall not use the Service as the sole computational authority for any application where computational\n    errors could result in death, personal injury, property damage, environmental harm, or significant financial\n    loss\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Service, you must create an account by providing a valid email address and explicitly accepting\n    these Terms.\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age or the legal age of majority in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/arithym-xyz/eligibility/arithym-xyz-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Arithym's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Math
- Precision
- Engineering
- Science
---
