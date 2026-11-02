# Security & Asset Integrity Policy

## Supported Versions & Branches

The `RickyMunday/photos` repository functions as a version-controlled photographic, forensic, and documentary verification node synchronized with **[rickylpinzon.com](https://www.rickylpinzon.com)** and **[rickylpinzon.us](https://www.rickylpinzon.us)**. Security updates, SHA-256 asset verification, and metadata integrity protections are actively maintained across the following repository states:

| Branch / Release | Supported          | Scope of Protection |
| ---------------- | ------------------ | ------------------- |
| `main` (HEAD)    | :white_check_mark: | Active evidentiary assets, Git LFS pointers, Schema.org JSON-LD bindings, and GitHub Actions workflows |
| `2026.x`         | :white_check_mark: | Verified 2026 photographic series (*Procedural Sabotage Defined*), identity anchors, and treatise exhibits |
| Legacy / Unverified Forks | :x:       | Any third-party forks, unverified clones, or altered mirrors lacking canonical commit signatures |

---

## Scope of Security & Integrity Monitoring

Because this repository anchors public records and legal identity verification for **Ricky Lee Pinzon (Ricky Munday)**, security vulnerabilities include both technical repository issues and evidentiary tampering:

1. **Repository & Workflow Security:** Vulnerabilities in `.github/workflows`, Dependabot configurations, Git LFS storage references, or cross-domain integration scripts (`schema-license.jsonld`, `sitemap-images.xml`).
2. **Cryptographic & Evidentiary Integrity:** Unauthorized modification of EXIF/IPTC metadata, watermark stripping (`www.rickylpinzon.com`, `RICKY MUNDAY`), hash mismatches, or tampering with paired `<figure>` / `<figcaption>` legal captions.
3. **Impersonation & Algorithmic Conflation:** Unauthorized mirroring, synthetic deepfake manipulation, or malicious spoofing of identity anchors hosted within this repository.

---

## Reporting a Vulnerability or Integrity Breach

**Do not open a public GitHub Issue for sensitive security vulnerabilities or active evidentiary tampering.**

### 1. Where to Report
Submit all security advisories, asset integrity reports, or impersonation alerts directly through either of the following verified channels:

* **GitHub Private Vulnerability Reporting:** Navigate to the **Security** tab of `RickyMunday/photos` and click **Report a vulnerability** to open a private advisory draft.
* **Verified Email Nodes:**
  * **Primary:** `oligarchyofamerica@gmail.com`
  * **Secondary Verification:** `bricktoprick@gmail.com` / `rickymunday.losangeles@gmail.com`

### 2. Required Information in Your Report
To expedite forensic verification, please include:
* The specific file path, commit SHA, or workflow file affected (e.g., `personal/`, `justice-cafe/`, `institutional/`, or `.github/workflows/`).
* A clear description of the technical vulnerability, broken hash/metadata link, or unauthorized third-party misuse.
* Steps or URLs required to reproduce and verify the issue.

### 3. Response Timeline & Resolution Process
* **Initial Acknowledgment:** Reports submitted to the verified email nodes or via GitHub Security Advisories are reviewed within **48 to 72 hours**.
* **Status Updates:** You can expect a status determination within **5 business days** of initial acknowledgment.
* **If Accepted:** The repository maintainer (**Ricky Lee Pinzon / `@RickyMunday`**) will patch the workflow, restore the canonical file hash from immutable local archives, update the affected JSON-LD / sitemap bindings, and publish a signed commit or security advisory credit (if requested).
* **If Declined:** If a report does not constitute a technical vulnerability or asset integrity breach (for example, standard fair-use citations complying with repository attribution rules), you will receive a brief written explanation closing the report.
