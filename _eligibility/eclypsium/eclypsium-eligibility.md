---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Licensee” means the individual or legal entity purchasing and using the Eclypsium Products
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control and sanctions
    text: Licensee covenants that it shall not, directly or indirectly, sell, access or use or permit access to or use of the Eclypsium Products
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
name: Eclypsium
provenance_date: '2026-11-09'
provider_name: Eclypsium
provider_slug: eclypsium
slug: eclypsium-eligibility
source_date: '2026-11-09'
source_filename: eclypsium-eligibility.yml
source_heading: Eligibility
source_page: https://eclypsium.com/eula/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eclypsium\naid: eclypsium\nurl: https://eclypsium.com/eula/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “Licensee” means the individual or legal entity purchasing and using the Eclypsium Products\nrestricted_uses:\n- summary: Export control and sanctions\n  text: Licensee covenants that it shall not, directly or indirectly, sell, access or use or permit access to or\n    use of the Eclypsium Products\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eclypsium/eligibility/eclypsium-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Eclypsium's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Firmware Security
- Supply Chain Security
- Hardware Security
- Infrastructure Security
- Endpoint Security
- Threat Detection
---
