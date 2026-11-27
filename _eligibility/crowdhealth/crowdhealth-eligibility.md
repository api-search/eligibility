---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for visitors located within the United States.
  entity_types:
  - text: You must be at least 18 years old to be a Primary Member of CrowdHealth.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to be a Primary Member of CrowdHealth.
    value: '18'
  restricted_uses:
  - summary: Providing goods or services for crowdfunding approval
    text: provide goods or services in exchange for approval of crowdfunding requests
  - summary: Fraudulent activity
    text: perform any fraudulent activity including impersonating any person or entity, claiming a false affiliation or identity, accessing any other Member accounts without permission, submitting fraudulent medical bills or documentation, or falsifying your age or date of birth
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You hereby authorize us, through third parties, to validate information about you and your Account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CrowdHealth
provenance_date: '2026-11-09'
provider_name: CrowdHealth
provider_slug: crowdhealth
slug: crowdhealth-eligibility
source_date: '2026-11-09'
source_filename: crowdhealth-eligibility.yml
source_heading: Eligibility
source_page: https://www.joincrowdhealth.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CrowdHealth\naid: crowdhealth\nurl: https://www.joincrowdhealth.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for visitors located within the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to be a Primary Member of CrowdHealth.\nrestricted_uses:\n- summary: Providing goods or services for crowdfunding approval\n  text: provide goods or services in exchange for approval of crowdfunding requests\n- summary: Fraudulent activity\n  text: perform any fraudulent activity including impersonating\
  \ any person or entity, claiming a false affiliation\n    or identity, accessing any other Member accounts without permission, submitting fraudulent medical bills or\n    documentation, or falsifying your age or date of birth\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You hereby authorize us, through third parties, to validate information about you and your Account.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to be a Primary Member of CrowdHealth.\n"
source_yaml_url: https://artifacts.apis.io/crowdhealth/eligibility/crowdhealth-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from CrowdHealth's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Health Insurance
- Health Sharing
- Crowdfunding
- Medical Billing
- Consumer Health
- Insurance Alternative
- Fintech
---
