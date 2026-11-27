---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Das Angebot von Dollea richtet sich in erster Linie an Unternehmer im Sinne von § 14 BGB, Freiberufler sowie sonstige Selbstständige
    type: business
  - text: Privatpersonen können die Angebote ebenfalls nutzen, soweit sie die vorliegenden Bedingungen akzeptieren.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Other purposes need written consent
    text: Eine Nutzung zu anderen Zwecken (z. B. medizinische Eingriffe, die besonderen gesetzlichen Vorgaben unterliegen, oder völlig branchenfremde Tätigkeiten) ist nur nach ausdrücklicher vorheriger Zustimmung in Textform von Dollea zulässig.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Für die Nutzung des Online-Buchungssystems ist eine Registrierung erforderlich.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: dollea-de
provenance_date: '2026-11-09'
provider_name: dollea-de
provider_slug: dollea-de
slug: dollea-de-eligibility
source_date: '2026-11-09'
source_filename: dollea-de-eligibility.yml
source_heading: Eligibility
source_page: https://www.dollea.de/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: dollea-de\naid: dollea-de\nurl: https://www.dollea.de/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Das Angebot von Dollea richtet sich in erster Linie an Unternehmer im Sinne von § 14 BGB, Freiberufler sowie\n    sonstige Selbstständige\n- type: individual\n  text: Privatpersonen können die Angebote ebenfalls nutzen, soweit sie die vorliegenden Bedingungen akzeptieren.\nrestricted_uses:\n- summary: Other purposes need written consent\n  text: Eine Nutzung zu anderen Zwecken (z. B. medizinische Eingriffe, die besonderen\
  \ gesetzlichen Vorgaben unterliegen,\n    oder völlig branchenfremde Tätigkeiten) ist nur nach ausdrücklicher vorheriger Zustimmung in Textform von Dollea\n    zulässig.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Für die Nutzung des Online-Buchungssystems ist eine Registrierung erforderlich.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dollea-de/eligibility/dollea-de-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from dollea-de's own page on 2026-11-09.
synthetic: false
tags:
- Beauty
- Salon
- Munich
- Cosmetics
- Wellness
---
