---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is controlled and operated from facilities within the United States. StartEngine makes no representations that the Service is appropriate or available for use in any other jurisdictions.
  entity_types:
  - text: The Service is only available to individuals who are at least eighteen years old.
    type: individual
  - text: If you are accessing the Site and/or using the Services on behalf of an entity, such as your employer or a company you work for or control, you warrant and represent that you have the legal authority to bind that entity to these Terms of Use.
    type: business
  minimum_age:
    text: The Service is only available to individuals who are at least eighteen years old.
    value: '18'
  restricted_uses:
  - summary: Restricted territories
    text: Accessing the Service is prohibited from territories where the content on the Site is prohibited.
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: federal law requires StartEngine Primary to obtain, verify, and record information that identifies those with whom we transact securities business for offerings facilitated by StartEngine Primary.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: StartEngine
provenance_date: '2026-11-10'
provider_name: StartEngine
provider_slug: startengine
slug: startengine-eligibility
source_date: '2026-11-10'
source_filename: startengine-eligibility.yml
source_heading: Eligibility
source_page: https://www.startengine.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StartEngine\naid: startengine\nurl: https://www.startengine.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is controlled and operated from facilities within the United States. StartEngine makes no representations\n    that the Service is appropriate or available for use in any other jurisdictions.\nentity_types:\n- type: individual\n  text: The Service is only available to individuals who are at least eighteen years old.\n- type: business\n  text: If you are accessing the Site and/or using the Services on behalf of an entity, such as your employer or\n    a\
  \ company you work for or control, you warrant and represent that you have the legal authority to bind that\n    entity to these Terms of Use.\nrestricted_uses:\n- summary: Restricted territories\n  text: Accessing the Service is prohibited from territories where the content on the Site is prohibited.\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: federal law requires StartEngine Primary to obtain, verify, and record information that identifies those\n    with whom we transact securities business for offerings facilitated by StartEngine Primary.\nminimum_age:\n  value: '18'\n  text: The Service is only available to individuals who are at least eighteen years old.\n"
source_yaml_url: https://artifacts.apis.io/startengine/eligibility/startengine-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from StartEngine's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Investing
- Crowdfunding
- Private Markets
- Capital Markets
- Financial Services
- Transfer Agent
- Securities
---
