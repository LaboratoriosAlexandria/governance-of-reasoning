# Verification of Authorship and Integrity

## The Governance of Reasoning: Foundations of Epistemic Engineering
**First Edition — July 2026**

---

## Document Identity

| Field | Value |
|-------|-------|
| **Title** | The Governance of Reasoning: Foundations of Epistemic Engineering |
| **Author** | Javier Albuixech Carrascosa |
| **Edition** | First edition, July 2026 |
| **Pages** | 112 |
| **Format** | PDF 1.7 |

## Cryptographic Verification

| Field | Value |
|-------|-------|
| **SHA-256** | `ba2d4b05b462c5c38ebda07fb6af13c9db12d948f20f25bd5860cd498e730037` |
| **GPG Key ID** | `4A07EDFE63EFC1A4` |
| **GPG Fingerprint** | `2F64 C968 72BC 3ABD 73CF 40FB 4A07 EDFE 63EF C1A4` |
| **Key Owner** | Javier Albuixech Carrascosa <contacto@laboratoriosalexandria.com> |
| **ORCID** | [0009-0005-1218-0701](https://orcid.org/0009-0005-1218-0701) |

## How to Verify

1. Obtain the original PDF of the first edition.
2. Compute its SHA-256 hash:
   ```bash
   sha256sum The_Governance_of_Reasoning.pdf
   ```
3. Compare the output with the hash above. A match confirms the document has not been altered since this record was created.
4. The GPG signature on this repository's commit confirms the author's identity. Verify with:
   ```bash
   git log --show-signature
   ```

## Purpose

This repository does not contain the book's content. It exists solely as a public, immutable, cryptographically signed record of authorship, creation date, and document integrity for the first edition.

---

© 2026 Javier Albuixech Carrascosa. All rights reserved.
