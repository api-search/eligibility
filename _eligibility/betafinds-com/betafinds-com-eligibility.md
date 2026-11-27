---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By using the Site, you confirm that you have the legal capacity to enter into these Terms.
    value: null
  restricted_uses:
  - summary: Guaranteed-return and investment projects
    text: You may not post projects that promise users guaranteed income, profit, or return on investment, financial pyramids or Ponzi schemes, or that solicit investment, sell tokens (ICO/IEO, etc.), or conduct other financial operations without a lawful basis and disclosure of risks.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Startups are published after moderation.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BetaFinds
provenance_date: '2026-11-09'
provider_name: BetaFinds
provider_slug: betafinds-com
slug: betafinds-com-eligibility
source_date: '2026-11-09'
source_filename: betafinds-com-eligibility.yml
source_heading: Eligibility
source_page: https://betafinds.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BetaFinds\naid: betafinds-com\nurl: https://betafinds.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Guaranteed-return and investment projects\n  text: You may not post projects that promise users guaranteed income, profit, or return on investment, financial\n    pyramids or Ponzi schemes, or that solicit investment, sell tokens (ICO/IEO, etc.), or conduct other financial\n    operations without a lawful basis and disclosure of risks.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Startups\
  \ are published after moderation.\nminimum_age:\n  value: null\n  text: By using the Site, you confirm that you have the legal capacity to enter into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/betafinds-com/eligibility/betafinds-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from BetaFinds's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Startups
- Platform
- Community
- Discovery
---
