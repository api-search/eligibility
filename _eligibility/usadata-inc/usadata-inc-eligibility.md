---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are acting in a broker capacity in the placement of orders on behalf your client ("Client"), then by accepting the terms and conditions of this Agreement, you hereby certify that you have the authority as a legal agent to bind your client
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitor access restriction
    text: 'Customer may not place orders for, sublicense or otherwise make the Products available to the following USADATA competitors: Acxiom, Experian, Equifax, Corelogic, Infogroup, Epsilon, KnowledgeBase Marketing ("KBM"); Central Address Systems ("CAS"), Merkle and Allant Group.'
  - summary: PersonicX industry restriction
    text: Customer is prohibited from marketing and/or providing PersonicX analytic reports that are based upon or that utilize syndicated data to any Client that falls within the following industries
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
name: USADATA
provenance_date: '2026-11-10'
provider_name: USADATA
provider_slug: usadata-inc
slug: usadata-inc-eligibility
source_date: '2026-11-10'
source_filename: usadata-inc-eligibility.yml
source_heading: Eligibility
source_page: https://www.usadata.com/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: USADATA\naid: usadata-inc\nurl: https://www.usadata.com/termsofuse\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are acting in a broker capacity in the placement of orders on behalf your client (\"Client\"), then\n    by accepting the terms and conditions of this Agreement, you hereby certify that you have the authority as a\n    legal agent to bind your client\nrestricted_uses:\n- summary: Competitor access restriction\n  text: 'Customer may not place orders for, sublicense or otherwise make the Products available to the following\n\
  \    USADATA competitors: Acxiom, Experian, Equifax, Corelogic, Infogroup, Epsilon, KnowledgeBase Marketing (\"KBM\");\n    Central Address Systems (\"CAS\"), Merkle and Allant Group.'\n- summary: PersonicX industry restriction\n  text: Customer is prohibited from marketing and/or providing PersonicX analytic reports that are based upon or\n    that utilize syndicated data to any Client that falls within the following industries\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/usadata-inc/eligibility/usadata-inc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from USADATA's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Marketing
- Data Enrichment
- Audience Targeting
- Data Hygiene
- Direct Mail
- Leads
- SOAP
- Mailing Lists
---
