# CV reference review and positioning

## Purpose

Use real CVs as evidence of how experienced engineers communicate scope, responsibility, technical judgment, and outcomes. They are not templates to copy, and the claims in them are not independently verified. The aim is to improve Kacper's interview chances for well-paid, interesting DevOps/platform roles while representing his experience accurately enough to avoid a poor-fit role.

## References reviewed

The most useful local documents were:

- `cvs/About Me _ Writing about code, electronics and other stuff.pdf` — Marcin Komsta, Warsaw-based Senior Cloud Platform Engineer; 11 years; migration of roughly 50 services to Kubernetes/Istio/FluxCD; infrastructure modernization and developer enablement.
- `cvs/Resume.pdf` — Joshua M. Holland, Lead DevOps Engineer; sole/broad ownership across infrastructure, developer tooling, integrations, security posture, and legal obligations for a distributed team.
- `cvs/mohamed-cv.pdf` — Mohamed Awad, AWS Cloud Engineer; 9 EKS clusters, 200+ microservices, Backstage/FastAPI developer platform, self-service workflows.
- `cvs/document.pdf` — Gunwant Jain, infrastructure/backend; deep Linux/Kubernetes/networking and infrastructure breadth, with concrete migration and platform work.
- `cvs/ojford-cv-2026-01-30.pdf` — Oliver Ford, senior IC/technical leader; nine years, pragmatic cost-aware designs, supporting junior colleagues, process and peer learning.
- `cvs/David Beck Resume.pdf` — David Beck, SRE; Linux and Windows automation, tooling, deployments, infrastructure support.
- `cvs/Jonathan Barnes's Resume.pdf` — Jonathan Barnes, physicist turned infrastructure engineer; end-to-end Linux fleet operations and customer/business responsibility.
- `cvs/fulcrumops-resume.pdf` / `cvs/resume-2.pdf` — duplicate Pete Emerson / FulcrumOps resumes; consulting, customer onboarding, AWS reference architectures, CI/CD and infrastructure implementation.
- `cvs/ThomasHahnResume.pdf` / `cvs/thomas-hahn-sre-resume.pdf` — duplicate Thomas Hahn resumes; DevOps consulting, productionization, Kubernetes, build systems, engineering productivity.
- `cvs/Resume-3.pdf` — Quan Tong Anh, software/DevOps engineer; career progression between systems administration, automation, and backend engineering.
- `cvs/cv.pdf` — Piper McCorkle, systems engineer at Cloudflare; global load balancing and waiting-room systems.
- `cvs/Jesse Adelman's resume.pdf` — senior SRE/consultant; broad, long-form project history and technical leadership.
- `cvs/John Mitchell 2024c-se.pdf` — senior/staff software and infrastructure engineer; security, cloud architecture, observability, DevEx.
- `cvs/resume-4.pdf` — Jerred Shepherd; technical leadership across a cross-functional, multi-service product migration.

## Patterns worth borrowing

### 1. Make responsibility explicit and bounded

The best examples make it clear whether the candidate owned a service, led a migration, operated a fleet, built a platform, or contributed to a team. For Kacper, this distinction matters: the AI publishing platform and iPhone device farm are individual-owner stories; CI/CD and developer tooling were shared; broader DevOps infrastructure was mostly owned by other teammates. State those boundaries directly. Credibility is a strength, not a concession.

### 2. Give scale a useful denominator

Scale is clearest when the reader can picture who or what depended on the work: services migrated, teams enabled, clusters operated, jobs moved, articles published, business audience reached, or years maintained. Good examples include 50 services, 9 clusters/200+ microservices, and systems serving many engineers. For Kacper, known evidence already includes around 400 Jenkins jobs, an organization growing from about 180 to 300+ people, over one million articles, and more than half of marketing-site Google Search traffic since tracking began. Use only figures that can be explained and qualified.

### 3. Show lifecycle ownership, not just build activity

Architecture + implementation + monitoring + ongoing operations + iteration is a strong senior signal. Several references show long-running ownership, customer onboarding, incident/production responsibility, or platform evolution. Kacper's article platform is unusually strong here: architecture, build, runtime monitoring, business-performance measurement through Analytics/Marketo, director/CEO/marketing stakeholder alignment, two years of maintenance, and expansion to new article types.

### 4. Explain the outcome before the tool inventory

The most readable bullets lead with the system or change and its result, then name relevant tools. Tool lists are useful for matching roles but weak as the main evidence. Keep the skills section compact; use bullets to show what Terraform, Jenkins, Prometheus, etc. enabled.

### 5. Seniority can be shown without people management

The references show seniority through technical decisions, independent delivery, stakeholder coordination, standards, mentoring, operational ownership, and cross-team enablement. Kacper need not claim management or broad infrastructure ownership. The AI platform's coordination with the director of engineering, CEO, and marketing team demonstrates influence; the device farm demonstrates autonomous technical execution across organizational boundaries.

### 6. Use detail selectively

Many real resumes are noisy: long skill inventories, multi-page histories, generic summaries, and bullets that describe duties without outcomes. Do not copy their length. A one-page CV should prioritize the two end-to-end ownership projects, then compress shared platform work and older roles.

## Recommended positioning

Target **Senior DevOps Engineer / Platform Engineer** roles where the job combines hands-on delivery, developer enablement, CI/CD, automation, and operational responsibility. Also consider DevOps roles in product companies where end-to-end project ownership is valued. Evaluate roles carefully when they imply sole ownership of a large production AWS estate, deep EKS/Kubernetes architecture, formal SRE/SLO ownership, or people leadership: those are not established by the current CV and shouldn't be implied.

The positioning should be: **hands-on DevOps/platform engineer who takes projects from ambiguous need through design, delivery, observability, stakeholder alignment, and ongoing operation; experienced with CI/CD and automation in a team setting.** This is stronger and more accurate than presenting as owner of the entire cloud estate.

## Evidence ledger for the CV

| Story | Personal responsibility | Team context / boundary | Evidence to use |
|---|---|---|---|
| AI article publishing platform | Main owner: designed architecture, implemented it, instrumented job health and article performance (Google Analytics/Marketo), aligned with stakeholders, maintained for two years, expanded article types | Built within Sensor Tower; do not imply sole ownership of AWS/DevOps estate | 1M+ articles; more than half of marketing website Google Search traffic since tracking began; duration and stakeholder set |
| iPhone analysis device farm | Main technical owner for relocation/rebuild; handled hardware, ISP/network, firewall, AWS connectivity, Prometheus monitoring; restored inherited service and fixed application deadlock | Specific project ownership, not overall Equinix infrastructure ownership | Bare-metal lab relocation/rebuild in Equinix Warsaw; list components personally handled |
| CI/CD / developer tooling | Shared work with manager and DevOps colleagues; contributions include IaC expansion, ~400 Jenkins jobs migrated to Job DSL, drift detection, runtime and cost optimization | Explicitly shared; broader infrastructure mostly other DevOps teammates | ~400 jobs; runtime example 15.5 to 12 min and 20%+ reductions in some periods; ARM/Ubuntu migration and cost practices |
| Equinix CI migration | Maintained Jenkins shared library/internal GitHub Actions, runners on Rancher Kubernetes, coordinated communication and task prioritization | Team/company-wide migration; don't imply sole lead unless confirmed | Cross-company change, documentation repository adoption/star result (verify before keeping) |

## CV revision decisions

1. Lead Sensor Tower with the AI platform as an end-to-end ownership story.
2. Give the iPhone device farm a concise, distinct bullet; avoid burying it under the AI achievement.
3. Consolidate shared CI/CD/IaC/performance/cost responsibilities into two bullets with precise attribution.
4. Remove the standalone long tech-stack bullet if it crowds out evidence; retain technologies in the skills section and weave high-value tools into bullets.
5. Keep Equinix compact but improve the migration/platform outcomes where facts support them.
6. Keep older roles brief. Add no claims based solely on reference CVs.

## Hiring-fit boundary

The aim is a role that stretches Kacper without requiring a false claim of being the sole architect/operator of an entire cloud organization. Prefer jobs that value project ownership, automation, CI/CD, developer experience, observability, and collaboration with product/engineering teams. During screening, clarify team size, on-call expectations, cloud/Kubernetes ownership, incident authority, and whether the role is building a platform with peers or acting as the only infrastructure engineer.

This review is qualitative. Public CVs and HN posts provide examples of presentation, not reliable evidence about interview conversion or market outcomes.
