---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: StatMuse+ is only available to users located in the United States of America, any use or attempted purchase of StatMuse+ by individuals or organizations located outside of the United States is prohibited.
  entity_types:
  - text: The Service is intended solely for persons who are (i) 18 or older, or (ii) 13 and older if either (a) an emancipated minor, or (b) he/she possess legal parental or guardian consent.
    type: individual
  - text: For enterprise data or content licensing inquiries, contact api@statmuse.com .
    type: business
  minimum_age:
    text: The Service is intended solely for persons who are (i) 18 or older, or (ii) 13 and older if either (a) an emancipated minor, or (b) he/she possess legal parental or guardian consent.
    value: '13'
  restricted_uses:
  - summary: Non-commercial use only
    text: Your use of the Service and the StatMuse Content is for your own personal and non-commercial use only.
  - summary: API data not to be monetized
    text: Use of the StatMuse API and StatMuse MCP shall be limited to non-commercial internal uses whereby the data returned by the StatMuse API and/or MCP is not directly or indirectly monetized in any manner whatsoever.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: StatMuse may approve, deny, suspend, throttle, or revoke API or MCP access, and any API key, at any time, for any reason, without notice.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: StatMuse
provenance_date: '2026-11-10'
provider_name: StatMuse
provider_slug: statmuse
slug: statmuse-eligibility
source_date: '2026-11-10'
source_filename: statmuse-eligibility.yml
source_heading: Eligibility
source_page: https://www.statmuse.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StatMuse\naid: statmuse\nurl: https://www.statmuse.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: StatMuse+ is only available to users located in the United States of America, any use or attempted purchase\n    of StatMuse+ by individuals or organizations located outside of the United States is prohibited.\nentity_types:\n- type: individual\n  text: The Service is intended solely for persons who are (i) 18 or older, or (ii) 13 and older if either (a) an\n    emancipated minor, or (b) he/she possess legal parental or guardian consent.\n- type: business\n  text: For\
  \ enterprise data or content licensing inquiries, contact api@statmuse.com .\nrestricted_uses:\n- summary: Non-commercial use only\n  text: Your use of the Service and the StatMuse Content is for your own personal and non-commercial use only.\n- summary: API data not to be monetized\n  text: Use of the StatMuse API and StatMuse MCP shall be limited to non-commercial internal uses whereby the data\n    returned by the StatMuse API and/or MCP is not directly or indirectly monetized in any manner whatsoever.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: StatMuse may approve, deny, suspend, throttle, or revoke API or MCP access, and any API key, at any time,\n    for any reason, without notice.\nminimum_age:\n  value: '13'\n  text: The Service is intended solely for persons who are (i) 18 or older, or (ii) 13 and older if either (a) an\n    emancipated minor, or (b) he/she possess legal parental or guardian consent.\n"
source_yaml_url: https://artifacts.apis.io/statmuse/eligibility/statmuse-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from StatMuse's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sports
- Statistics
- Search
- Natural-Language
- Data
- Finance
- Analytics
---
