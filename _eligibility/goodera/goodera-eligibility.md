---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF THE INDIVIDUAL ENTERING INTO THIS AGREEMENT IS DOING SO ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, SUCH INDIVIDUAL REPRESENTS THAT HE OR SHE HAS THE REQUISITE AUTHORITY TO BIND SUCH ENTITY
    type: business
  minimum_age:
    text: Use of the Service by anyone under the age of 18 is prohibited.
    value: '18'
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
name: Goodera
provenance_date: '2026-11-09'
provider_name: Goodera
provider_slug: goodera
slug: goodera-eligibility
source_date: '2026-11-09'
source_filename: goodera-eligibility.yml
source_heading: Eligibility
source_page: https://www.goodera.com/pages/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Goodera\naid: goodera\nurl: https://www.goodera.com/pages/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF THE INDIVIDUAL ENTERING INTO THIS AGREEMENT IS DOING SO ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY,\n    SUCH INDIVIDUAL REPRESENTS THAT HE OR SHE HAS THE REQUISITE AUTHORITY TO BIND SUCH ENTITY\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Use of the Service by anyone under the age of 18 is prohibited.\n"
source_yaml_url: https://artifacts.apis.io/goodera/eligibility/goodera-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Goodera's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Corporate Volunteering
- Social Impact
- CSR
- Employee Engagement
- Non-Profit
- Event
- Volunteering
- ESG
- MCP
---
