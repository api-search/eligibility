---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Kunde kann sowohl ein Unternehmer nach § 14 BGB als auch ein Verbraucher nach § 13 BGB sein.
    type: business
  - text: Verbrauchern steht ein gesetzliches Widerrufsrecht zu.
    type: individual
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Der Kunde registriert sich mit seiner E-Mail-Adresse und einem selbst gewählten Passwort und bestätigt die Adresse über den ihm zugesandten Link.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: asksteps
provenance_date: '2026-11-09'
provider_name: asksteps
provider_slug: asksteps-co
slug: asksteps-co-eligibility
source_date: '2026-11-09'
source_filename: asksteps-co-eligibility.yml
source_heading: Eligibility
source_page: https://asksteps.co/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: asksteps\naid: asksteps-co\nurl: https://asksteps.co/agb\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Kunde kann sowohl ein Unternehmer nach § 14 BGB als auch ein Verbraucher nach § 13 BGB sein.\n- type: individual\n  text: Verbrauchern steht ein gesetzliches Widerrufsrecht zu.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Der Kunde registriert sich mit seiner E-Mail-Adresse und einem selbst gewählten Passwort und bestätigt die\n    Adresse über den ihm zugesandten Link.\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/asksteps-co/eligibility/asksteps-co-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 3 quoted statements, read from asksteps's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Forms
- PDFs
- Funnels
- Automation
- Developer Tools
---
