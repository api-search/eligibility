---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Fannie Mae operates this Web site from the United States of America. Access to Contents from jurisdictions where such access is illegal is prohibited.
  entity_types:
  - text: available for use only by lenders, originators or other businesses (the "Licensed Users") that have entered into a currently effective license agreement
    type: business
  - source: https://www.fanniemae.com/tech-guide
    text: Any entity that is not currently a Licensee and wishes to have access to one or more Fannie Mae applications will need to execute a Software Subscription License or electronically consent to its terms.
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Access to password-protected licensed products
    text: Password-Protected Areas contain applications (such as Desktop Originator® and Desktop Underwriter®), manuals, forms, and other documents or programs
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: available for use only by lenders, originators or other businesses (the "Licensed Users") that have entered into a currently effective license agreement
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fannie Mae
provenance_date: '2026-11-09'
provider_name: Fannie Mae
provider_slug: fannie-mae
slug: fannie-mae-eligibility
source_date: '2026-11-09'
source_filename: fannie-mae-eligibility.yml
source_heading: Eligibility
source_page: https://www.fanniemae.com/about-us/legal-disclosure
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fannie Mae\naid: fannie-mae\nurl: https://www.fanniemae.com/about-us/legal-disclosure\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.fanniemae.com/about-us/legal-disclosure\n  - https://www.fanniemae.com/tech-guide\ncountries:\n  served: []\n  excluded: []\n  text: Fannie Mae operates this Web site from the United States of America. Access to Contents from jurisdictions\n    where such access is illegal is prohibited.\nentity_types:\n- type: business\n  text: available for use only by lenders, originators or other businesses (the \"Licensed Users\") that have entered\n    into a currently effective license\
  \ agreement\n- type: other\n  text: Any entity that is not currently a Licensee and wishes to have access to one or more Fannie Mae applications\n    will need to execute a Software Subscription License or electronically consent to its terms.\n  source: https://www.fanniemae.com/tech-guide\nrestricted_uses:\n- summary: Access to password-protected licensed products\n  text: Password-Protected Areas contain applications (such as Desktop Originator® and Desktop Underwriter®), manuals,\n    forms, and other documents or programs\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: available for use only by lenders, originators or other businesses (the \"Licensed Users\") that have entered\n    into a currently effective license agreement\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fannie-mae/eligibility/fannie-mae-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Fannie Mae's own page on 2026-11-09.
synthetic: false
tags:
- Housing
- Mortgage
- Finance
- Government-Sponsored Enterprise
- Fortune 100
---
