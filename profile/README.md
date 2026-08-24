# MatrixGard

> **Fractional DevSecOps for pre-seed and seed startups.** We become your cloud, infrastructure, and security team on a monthly retainer for a fraction of the cost of a senior hire. Operating across India, Singapore, UAE, UK, and US.

🌐 [matrixgard.com](https://matrixgard.com/?utm_source=github&utm_medium=org_readme&utm_content=home) &nbsp;·&nbsp; 📧 avinash@matrixgard.com &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/company/matrixgard-com) &nbsp;·&nbsp; 🐦 [@matrixgard](https://x.com/matrixgard)

---

## What we publish here

This GitHub organization is where MatrixGard ships the parts of our practice that work better as open source than as a slide deck, opinionated baselines, real-world tooling, and the kind of "we wish someone had handed us this on day one" infrastructure templates that cut months off a startup's security and reliability roadmap.

Every artifact published here is **opinionated**, **documented with the why**, and **honest about what it doesn't do**. We'd rather ship one truly useful module than ten generic ones.

### Live

- [**aws-startup-security-baseline**](https://github.com/avinash-matrixgard/aws-startup-security-baseline): The 12 AWS security controls every 5-engineer seed startup should turn on this afternoon, and the 80 CIS controls you can skip until Series A. Single Terraform module, ~$10–40/month at startup scale, ~22 AWS resources, full per-control deep-dive docs.

### Coming soon

- **devsecops-ci-templates**: Reusable GitHub Actions workflows for Trivy container scans, Snyk dependency scans, OWASP ZAP DAST, Semgrep SAST, and IAM policy linting. Drop-in `.github/workflows/` templates with sane defaults that fail-soft until you're ready to gate.
- **seed-startup-security-checklist**: Living markdown checklist for AWS account hardening, DPDP Act readiness, RBI fintech baseline, SOC 2 prep, and incident response readiness. Forkable, with cross-references to long-form blog posts at matrixgard.com.

---

## What MatrixGard does (the paid part)

We solve the pre-seed founder problem: **you need cloud architecture, CI/CD automation, and security expertise, three separate disciplines, but you can only afford one senior hire who cannot credibly be all three.**

We become that team on retainer. One Slack channel. One invoice. Senior capacity from day one, no recruiter fees, no 6-month ramp, no equity dilution.

**Service areas:**

- AWS, GCP, and Azure security baselines
- CI/CD pipeline security (Trivy, Snyk, OWASP ZAP)
- FinOps and cloud cost optimization
- SOC 2, ISO 27001, RBI Master Direction, DPDP Act, PCI-DSS compliance preparation
- Kubernetes hardening
- Incident response readiness for fintech 6-hour reporting requirements

**Engagement model:** Free 20-minute infrastructure review → fixed-scope audit OR monthly retainer (from Rs 40,000/month). No long-term lock-in.

[**Book a free 20-minute infrastructure review →**](https://matrixgard.com/book?utm_source=github&utm_medium=org_readme&utm_content=book)

---

## Real client results

From our public case study with [saysri.ai](https://matrixgard.com/case-studies/saysri-audit/?utm_source=github&utm_medium=org_readme&utm_content=case_studies_saysri_audit), an AI recruitment platform on Microsoft Azure:

> **Before:** TLS 1.0 enabled, public blob storage, no WAF, orphaned cloud resources bleeding money quietly.
>
> **After:** 8 critical security vulnerabilities fixed, 70% of orphaned cloud resources eliminated, production-grade security posture achieved, in 7 working days.

> *"MatrixGard have recommended robust security practices which made our app resilient and helped us to cut unnecessary cloud infrastructure costs which we reinvested on our product development."*, Sayeenath, saysri.ai

---

## About the founder

**Avinash S**, almost a decade building, breaking, and securing cloud infrastructure across India, Singapore, UAE, UK, and US. Founded MatrixGard in 2024 to solve the pre-seed problem at scale.

**Specialties:** AWS, GCP, Azure, Kubernetes, Terraform, FinOps, DevSecOps, incident response, multi-agent AI architectures.

**Find Avinash:** [LinkedIn](https://www.linkedin.com/in/avinash-s-devsecops/) &nbsp;·&nbsp; [X / Twitter](https://x.com/matrixgard) &nbsp;·&nbsp; [GitHub](https://github.com/avinash-matrixgard) &nbsp;·&nbsp; [DEV.to](https://dev.to/saavinash)

---

## Read more

- [**Blog**](https://matrixgard.com/blog?utm_source=github&utm_medium=org_readme&utm_content=blog): long-form posts on AWS IAM auditing, RBI compliance for fintech, cloud cost optimization, the architecture behind Ghost-hunter (our internal AI cloud-bill investigator), and what we found auditing 30 startups
- [**Services**](https://matrixgard.com/services?utm_source=github&utm_medium=org_readme&utm_content=services): full service catalogue and pricing tiers
- [**Pricing**](https://matrixgard.com/pricing?utm_source=github&utm_medium=org_readme&utm_content=pricing): transparent monthly retainers and audit packages
- [**About**](https://matrixgard.com/about?utm_source=github&utm_medium=org_readme&utm_content=about): who we are, who we serve, and what we deliberately don't do

---

## Contributing

Most published modules accept community contributions. The bar is consistent across every repo:

- Every new control / template / checklist item must come with a *why we add it*, *what breaks if you skip it*, and *when to graduate off it*, same template the existing entries use
- ASCII-safe text in all docs (some directories strip Unicode silently)
- No fabricated client work, no inflated outcomes, no inventing testimonials

Each repo's `CONTRIBUTING.md` has the full PR checklist.

---

## Get in touch

- **Free infrastructure review:** [matrixgard.com/book](https://matrixgard.com/book?utm_source=github&utm_medium=org_readme&utm_content=book)
- **Email:** avinash@matrixgard.com
- **Issues / PRs / questions:** file in the relevant repo, or email if you want to talk first

---

*MatrixGard is operated by NASHSMATRIXGARD OPC PVT LTD, a One Person Company registered in Chennai, India. Founded 2024. All published code is MIT licensed unless noted otherwise.*
