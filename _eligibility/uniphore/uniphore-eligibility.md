---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: Customer is not located in, organized under the laws of, or ordinarily resident in any country or territory that is subject to comprehensive export controls or a comprehensive U.S. government embargo or sanctions program (including, as of the Effective Date, Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk, and Luhansk regions of Ukraine)
  entity_types:
  - text: the entity or individual identified in the applicable Order Form (“ Customer ”)
    type: individual
  - text: If Customer is agreeing to this Agreement on behalf of an entity, Customer represents and warrants that it has authority to bind such entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited end uses (WMD, missile, military)
    text: Customer will not use the Services for any prohibited end use, including, but not limited to, the development, production, or proliferation of weapons of mass destruction, missile technology, or military end uses in restricted countries
  - summary: Customer-submitted PHI and card data
    text: Customer must not submit protected health information (PHI) under HIPAA or payment card data subject to PCI-DSS to the Services unless the applicable Services are identified in the Order Form as certified and scoped for the applicable compliance requirement
  - source: https://www.uniphore.com/legal/aup/
    summary: Unlicensed professional advice
    text: Provide advice that requires a professional license, such as legal or medical advice, without the appropriate involvement of a qualified, licensed professional.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Uniphore
provenance_date: '2026-11-10'
provider_name: Uniphore
provider_slug: uniphore
slug: uniphore-eligibility
source_date: '2026-11-10'
source_filename: uniphore-eligibility.yml
source_heading: Eligibility
source_page: https://www.uniphore.com/legal/msa/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Uniphore\naid: uniphore\nurl: https://www.uniphore.com/legal/msa/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.uniphore.com/legal/aup/\n  - https://www.uniphore.com/legal/msa/\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: Customer is not located in, organized under the laws of, or ordinarily resident in any country or territory\n    that is subject to comprehensive export controls or a comprehensive U.S. government embargo or sanctions program\n    (including, as of the Effective Date, Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk, and Luhansk regions\n \
  \   of Ukraine)\nentity_types:\n- type: individual\n  text: the entity or individual identified in the applicable Order Form (“ Customer ”)\n- type: business\n  text: If Customer is agreeing to this Agreement on behalf of an entity, Customer represents and warrants that\n    it has authority to bind such entity.\nrestricted_uses:\n- summary: Prohibited end uses (WMD, missile, military)\n  text: Customer will not use the Services for any prohibited end use, including, but not limited to, the development,\n    production, or proliferation of weapons of mass destruction, missile technology, or military end uses in restricted\n    countries\n- summary: Customer-submitted PHI and card data\n  text: Customer must not submit protected health information (PHI) under HIPAA or payment card data subject to\n    PCI-DSS to the Services unless the applicable Services are identified in the Order Form as certified and scoped\n    for the applicable compliance requirement\n- summary: Unlicensed professional\
  \ advice\n  text: Provide advice that requires a professional license, such as legal or medical advice, without the appropriate\n    involvement of a qualified, licensed professional.\n  source: https://www.uniphore.com/legal/aup/\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/uniphore/eligibility/uniphore-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 6 quoted statements, read from Uniphore's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agents
- Conversational AI
- Customer Data Platform
- Contact Center
- Machine Learning
- LLM
- Enterprise Software
- Automation
- Customer Experience
- Knowledge Management
---
