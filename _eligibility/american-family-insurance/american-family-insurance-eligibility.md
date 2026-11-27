---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Platforms are designed for residents of the United States only and should not be considered a solicitation to buy or an offer to sell products and services in any other jurisdiction.
  entity_types:
  - text: If you are below the age of 18, you may download, install, access or use our Platforms only under the supervision of a parent or legal guardian who agrees to be bound by these Terms.
    type: individual
  minimum_age:
    text: If you are below the age of 18, you may download, install, access or use our Platforms only under the supervision of a parent or legal guardian who agrees to be bound by these Terms.
    value: '18'
  restricted_uses:
  - summary: Unlawful or disruptive use
    text: 'You may not, and you may not authorize, encourage, or support a third party’s attempts to, use the Platforms in any way that is unlawful or that: Damages, disrupts, overburdens, interferes, or impairs the Platforms'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Your eligibility to purchase our products is subject to your application and review and qualification by American Family in its sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: American Family Insurance
provenance_date: '2026-11-09'
provider_name: American Family Insurance
provider_slug: american-family-insurance
slug: american-family-insurance-eligibility
source_date: '2026-11-09'
source_filename: american-family-insurance-eligibility.yml
source_heading: Eligibility
source_page: https://www.amfam.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: American Family Insurance\naid: american-family-insurance\nurl: https://www.amfam.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Platforms are designed for residents of the United States only and should not be considered a solicitation\n    to buy or an offer to sell products and services in any other jurisdiction.\nentity_types:\n- type: individual\n  text: If you are below the age of 18, you may download, install, access or use our Platforms only under the supervision\n    of a parent or legal guardian who agrees to be bound by these Terms.\n\
  restricted_uses:\n- summary: Unlawful or disruptive use\n  text: 'You may not, and you may not authorize, encourage, or support a third party’s attempts to, use the Platforms\n    in any way that is unlawful or that: Damages, disrupts, overburdens, interferes, or impairs the Platforms'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Your eligibility to purchase our products is subject to your application and review and qualification by\n    American Family in its sole discretion.\nminimum_age:\n  value: '18'\n  text: If you are below the age of 18, you may download, install, access or use our Platforms only under the supervision\n    of a parent or legal guardian who agrees to be bound by these Terms.\n"
source_yaml_url: https://artifacts.apis.io/american-family-insurance/eligibility/american-family-insurance-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from American Family Insurance's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Auto Insurance
- Home Insurance
- Life Insurance
- Property and Casualty
- Financial Services
- Fortune 500
---
