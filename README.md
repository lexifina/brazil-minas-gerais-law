# Minas Gerais: law history in git

The law of the State of Minas Gerais, Brazil, in Portuguese: one file per article and one paragraph per line. This record follows the shared design of lexifina/global-law.

## What this repository holds

| Folder | Act | Versions |
| --- | --- | ---: |
| `constituicao/` | State Constitution | 1 |
| `adt-1989/` | Constitutional transitional provisions | 1 |
| `lcp-2019-0149/` | LC 149/2019 | 2 |
| `lcp-2021-0160/` | LC 160/2021 | 2 |
| `lcp-2021-0165/` | LC 165/2021 | 2 |
| `lcp-2022-0167/` | LC 167/2022 | 2 |
| `lcp-2023-0171/` | LC 171/2023 | 4 |
| `lcp-2023-0172/` | LC 172/2023 | 2 |
| `lcp-2025-0180/` | LC 180/2025 | 2 |
| Other `lcp-<year>-<number>/` folders | Other complementary laws retained in the record | 1 each |
| `lei-<year>-<number>/`, `ldl-<year>-<number>/`, `del-<year>-<number>/`, `dec-<year>-<number>/` | Leis, Leis Delegadas, Decretos-Leis and Decretos from the ALMG records, being added in batches (records listing a total revocation left out) | 1 each |

The record contains 175 acts and 184 versions. LC 171/2023 also includes the wordings effective on 2023-12-28 and 2024-06-15, established by LC 172/2023 and LC 175/2024. Textual annexes are retained.

For other acts, an unaltered ALMG record is given as enacted; an altered record generally begins with its oldest available consolidated text. Ordinary laws, delegated laws, decree-laws and decrees are being added in batches by the same rule; constitutional amendments as separate acts are not included.

## Source

ALMG, Legislação Mineira (Dados Abertos), published by the Assembleia Legislativa do Estado de Minas Gerais. Each version identifies its official source URL and the SHA-256 of that response in data/versions.json.

## Dates

The added original texts use their official publication dates and their express publication-day commencement clauses. The two intermediate texts use the amending laws’ publication dates and express commencement clauses. Correction commits give these grounds in In-force-basis trailers. Commit authors are dated at noon in Belo Horizonte; the original published history remains intact.

For LC 149/2019, LC 165/2021 and LC 167/2022, ALMG identifies judicial publication or finality dates; this record does not establish the full chronology of injunctions, modulation or interpretation effects.

## Text and verification

Article headings, paragraphs and textual tables follow the official text. ALMG editorial annotations, struck-through historical passages in consolidated text and update timestamps are not treated as enacted wording. Original textual annexes and punctuation-only paragraphs are retained. No OCR is used for these history additions.

The seven original word streams and punctuation are compared with the complete official original text; intermediate changes are compared with the official amendment quotes, while all unaffected provisions remain unchanged. Readers reconstruct versions at their recorded dates, with labelled corrections applied. REPRODUCE.md records the structural and reproducibility checks.

## Attribution and limits

Authors identify the law responsible for the wording, or ALMG for a consolidated snapshot. Lexifina is the committer. This is a partial history, not a complete account of every intervening legal effect. Mixed commencement, later promulgation after rejected vetoes and some backdated source dates remain outside these history additions. Only the Diário Oficial is authoritative.

## Licence

Brazilian law texts are not protected by copyright under Lei 9.610/1998, article 8 IV; see LICENSE. Fonte: ALMG, Legislação Mineira (Dados Abertos), Assembleia Legislativa do Estado de Minas Gerais.

Este registro reúne textos oficiais de Minas Gerais e versões históricas identificadas. O Diário Oficial permanece a fonte autoritativa; a cronologia de todos os efeitos jurídicos não está integralmente representada.
