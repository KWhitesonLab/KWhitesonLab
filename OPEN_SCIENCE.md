# Sharing data, code and protocols — Whiteson Lab

Our goal is that anyone — a reviewer, a
reader, a future member of this lab — can find our work, understand it, and
reuse it legally, without having to email anyone. we also welcome emails and like to discuss our data and help someone use it!

Most of this takes minutes. The cost of skipping it lands years later, usually
on someone who has left and can no longer be reached.

---

## Defaults by output type

| Output | License | Where it goes |
|---|---|---|
| **Code** | MIT | GitHub, archived to Zenodo for a DOI |
| **Derived data** (tables, figure source data) | CC0 or CC BY | Zenodo or Dryad (free for UCI through our institutional membership) |
| **Raw sequencing** | — | NCBI SRA, under a BioProject cited in the paper |
| **Protocols** | CC BY | protocols.io |
| **Preprints** | CC BY | bioRxiv or medRxiv, posted at submission |
| **Strains, plasmids, phages** | — | Addgene, DSMZ, or BEI as appropriate |

If you are not sure which license, use **MIT for code** and **CC BY for
everything else**. Both are one click when you create the file on GitHub.

## Human subjects data — read this before releasing anything

Most of our microbiome work uses patient-derived samples: CF sputum, urine,
colonoscopy, pregnancy cohorts, clinical isolates. **The defaults above do not
override your IRB protocol or participant consent.**

- Raw human-derived sequencing goes to SRA with human reads removed, under the
  access terms your protocol allows. Controlled access is often correct.
- Never apply CC0 to data where consent does not permit unrestricted reuse.
- Metadata that could re-identify a participant — dates, locations, rare
  diagnoses in small cohorts — does not go in a public repository.
- When in doubt, ask Katrine before depositing, not after.

Open by default, but the default is not the rule when people's samples are
involved.

## When you submit a paper

Do these at submission, not at acceptance. Reviewers look.

- [ ] Repository exists and is **public**, with a name that says what it is
- [ ] **LICENSE** file present
- [ ] **README** with: the paper's citation, what's in each folder, and a
      figure-to-script map so a reader can find the code behind a given figure
- [ ] **CITATION.cff** so GitHub shows a "Cite this repository" button
- [ ] **Zenodo DOI** minted from a release (connect Zenodo to GitHub once,
      then it is automatic for every future release)
- [ ] Raw data deposited, accession in hand, **release date set to publication
      — not four years out**
- [ ] Data availability statement naming the specific repository URL and the
      accession, not an organization page and not "available on request"
- [ ] Software versions recorded (`sessionInfo()` covers the R side)
- [ ] Any AI assistance disclosed, in the paper and in the repo README

[GinaFaraci/TREM2-Metabolomics](https://github.com/GinaFaraci/TREM2-Metabolomics)
is a good model: license, clear README, raw data included, and a note about
which figures were made outside the code.

## Before you leave the lab

Work hosted on a personal account disappears when that account does. Before
you go:

- Mint a **Zenodo DOI** for every repo behind a paper. The DOI outlives the
  account, and it is the only step that genuinely protects the work.
- Make sure your README names **who wrote what**, so credit survives.
- Send Katrine your repo URLs so the lab index stays current.
- If a project never produced a repo, your **dissertation on eScholarship**
  is the archival record — make sure the analysis is described there.

## The lab index

[github.com/KWhitesonLab](https://github.com/KWhitesonLab) lists every
repository and the paper it belongs to. It is the lab's front door.

Repos stay under their authors' ownership on personal accounts; we index
rather than absorb them. When you publish something new, send the link.

---

*Adapted in part from the [Astera Institute's open science policy](https://astera.org/open-science-policy/),
with changes where our work involves human subjects and where our trainees
need peer-reviewed publications.*
_Disclosure: AI assisted_
