---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Czech VAT applies to companies registered in the Czech Republic. For VAT-registered companies elsewhere in the EU the invoice carries the reverse charge; outside the EU no Czech VAT is charged.
  entity_types:
  - text: Partnerships, company memberships, one-off reach items and community operations are invoiced by Engineering Leaders Community s.r.o.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Procurement teams that need a vendor form, a VAT certificate or a registry extract get them from marian@engineeringleaders.io.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: engineeringleaders-io
provenance_date: '2026-11-09'
provider_name: engineeringleaders-io
provider_slug: engineeringleaders-io
slug: engineeringleaders-io-eligibility
source_date: '2026-11-09'
source_filename: engineeringleaders-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.engineeringleaders.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: engineeringleaders-io\naid: engineeringleaders-io\nurl: https://www.engineeringleaders.io/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Czech VAT applies to companies registered in the Czech Republic. For VAT-registered companies elsewhere\n    in the EU the invoice carries the reverse charge; outside the EU no Czech VAT is charged.\nentity_types:\n- type: business\n  text: Partnerships, company memberships, one-off reach items and community operations are invoiced by Engineering\n    Leaders Community s.r.o.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: Procurement teams that need a vendor form, a VAT certificate or a registry extract get them from marian@engineeringleaders.io.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/engineeringleaders-io/eligibility/engineeringleaders-io-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 3 quoted statements, read from engineeringleaders-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Community
- Leadership
- Event
- Membership
---
