---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: if you are located in or ordinarily resident in a country or territory subject to comprehensive sanctions administered by the Office of Foreign Asset Control
  entity_types:
  - text: You may not access or use the Site or accept the Terms if you are not at least 18 years old.
    type: individual
  - text: By accessing or using the Site, you are accepting these Terms (on behalf of yourself or the entity that you represent)
    type: business
  minimum_age:
    text: You may not access or use the Site or accept the Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No use violating sanctions or export laws
    text: DZF does not encourage, induce, or sanction the deployment, integration, or use of the Site in violation of applicable laws or regulations and hereby prohibits any such deployment, integration or use.
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
name: DoubleZero
provenance_date: '2026-11-09'
provider_name: DoubleZero
provider_slug: doublezero
slug: doublezero-eligibility
source_date: '2026-11-09'
source_filename: doublezero-eligibility.yml
source_heading: Eligibility
source_page: https://doublezero.xyz/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DoubleZero\naid: doublezero\nurl: https://doublezero.xyz/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: if you are located in or ordinarily resident in a country or territory subject to comprehensive sanctions\n    administered by the Office of Foreign Asset Control\nentity_types:\n- type: individual\n  text: You may not access or use the Site or accept the Terms if you are not at least 18 years old.\n- type: business\n  text: By accessing or using the Site, you are accepting these Terms (on behalf of yourself or the entity that\n    you represent)\nrestricted_uses:\n- summary:\
  \ No use violating sanctions or export laws\n  text: DZF does not encourage, induce, or sanction the deployment, integration, or use of the Site in violation\n    of applicable laws or regulations and hereby prohibits any such deployment, integration or use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may not access or use the Site or accept the Terms if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/doublezero/eligibility/doublezero-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from DoubleZero's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web3
- DePIN
- Blockchain
- Networking
- Infrastructure
- Solana
- Low Latency
- Fiber Network
- CLI
---
