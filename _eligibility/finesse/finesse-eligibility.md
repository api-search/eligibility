---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission to use the Services and have gotten your parent or guardian to agree to these Terms on your behalf).
    type: individual
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under thirteen (13).
    value: '13'
  restricted_uses:
  - summary: Commercial or third-party use
    text: You will only use the Services and Products you obtain for your own internal, personal, non-commercial use, and not on behalf of or for the benefit of any third party
  - summary: Sanctioned jurisdictions (Apple App only)
    text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
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
name: FINESSE
provenance_date: '2026-11-09'
provider_name: FINESSE
provider_slug: finesse
slug: finesse-eligibility
source_date: '2026-11-09'
source_filename: finesse-eligibility.yml
source_heading: Eligibility
source_page: https://finesse.us/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FINESSE\naid: finesse\nurl: https://finesse.us/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Services and have gotten your parent or guardian\n    to agree to these Terms on your behalf).\nrestricted_uses:\n- summary: Commercial or third-party use\n  text: You will only use the Services and Products you obtain for your own internal,\
  \ personal, non-commercial use,\n    and not on behalf of or for the benefit of any third party\n- summary: Sanctioned jurisdictions (Apple App only)\n  text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo, or\n    that has been designated by the U.S. Government as a “terrorist supporting” country\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: We do not knowingly collect or solicit personally identifiable information from children under thirteen\n    (13).\n"
source_yaml_url: https://artifacts.apis.io/finesse/eligibility/finesse-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from FINESSE's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- E-Commerce
- Fashion
- Apparel
- Direct to Consumer
- Agentic Commerce
- Universal Commerce Protocol
- MCP
- Agent-Native
- Shopify
- Consumer
---
