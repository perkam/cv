# Senior DevOps / Platform development plan

## Goal

Build toward well-paid, interesting Senior DevOps / Platform roles while avoiding a mismatch where the job expects expertise or ownership not yet demonstrated. This plan distinguishes **application readiness** from **longer-term growth**. It is not a claim that every competency below is currently missing; validate each against actual job descriptions and interview feedback.

## Current strengths evidenced in the CV and project history

- AWS and infrastructure automation exposure: Terraform, Terragrunt, Ansible, Packer, Linux.
- CI/CD systems: Jenkins, Job DSL, GitHub Actions, self-hosted runners, workflow automation.
- Observability: Prometheus, Grafana, CloudWatch; monitoring experience across services and jobs.
- Delivery under constraints: performance/runtime tuning, CI cost awareness, ARM runner migration.
- End-to-end delivery: AI publishing platform and device farm ownership from design through operation.
- Cross-functional communication: coordination with engineering leadership, CEO, marketing, and company-wide migration participants.
- Breadth from backend/data engineering roles: Java, Go, Python, Azure, Kubernetes, ETL/ML workflows.

## Priority 1: Strengthen production reliability practice

**Why:** Senior infrastructure roles often expect sound operational decisions, not only provisioning and pipeline work. The CV has monitoring and restoration experience, but does not yet show a formal reliability framework such as SLIs/SLOs, error budgets, incident command, or post-incident review ownership.

**Learning / practice:**

- Choose a real service or homelab workload and define user-facing SLIs, an SLO, and alert thresholds.
- Create a small incident playbook and conduct a failure exercise (dependency outage, capacity exhaustion, or failed deployment).
- Write a blameless postmortem with detection time, impact, contributing factors, and follow-up actions.
- Practice distinguishing symptoms, causes, and actionable alerts; reduce noisy alerts.

**Evidence to add only after doing it:** an SLO-backed service, an incident/failure exercise, alert-noise reduction, recovery-time improvement, or a documented operational playbook.

## Priority 2: Deepen AWS architecture and operations

**Why:** AWS is central to the target roles and your CV. Interviewers may probe IAM, networking, account boundaries, availability, backup/restore, security, and cost decisions. Your own description makes clear that broad AWS infrastructure responsibility was mostly held by other DevOps teammates, so increased hands-on depth can grow capability without rewriting history.

**Learning / practice:**

- Build a small multi-environment AWS deployment using Terraform modules, remote state, IAM roles, and least-privilege policies.
- Include VPC/subnet/routing/security-group design, DNS/TLS, secrets, logging, and budget alarms.
- Implement backups and perform a restore test; document RPO/RTO assumptions.
- Compare a few architecture choices and tradeoffs (managed service vs EC2, availability vs cost, reserved/spot/on-demand).

**Evidence to add only after doing it:** an operated system with explicit architecture choices, restore results, security boundaries, or cost/performance measurements.

## Priority 3: Develop Kubernetes troubleshooting depth (role-dependent)

**Why:** It appears in target job families and your experience, but it is not the clearest current differentiator. Some senior jobs expect cluster administration; others only expect application/platform deployment familiarity. Match the depth to postings rather than treating “Kubernetes” as one skill.

**Learning / practice:**

- Operate a small cluster (k3s is sufficient for learning) and deploy a representative service.
- Practice debugging scheduling, resource pressure, probes, DNS/networking, storage, RBAC, and failed rollouts.
- Add GitOps and policy/security controls if they recur in target postings.
- Keep a troubleshooting journal with symptoms, hypotheses, commands, root cause, and prevention.

**Evidence to add only after doing it:** a cluster or workload you actually operated, problems solved, deployment/recovery improvements, or documented runbooks. Do not imply production EKS ownership if practice was homelab-only.

## Priority 4: Make platform work measurable through developer experience

**Why:** Platform roles increasingly focus on the engineers using the platform: reduced setup friction, faster feedback, self-service, adoption, and fewer repetitive support requests. Your Jenkins Job DSL migration and developer tooling work can be positioned this way if we can establish effects beyond the number of jobs migrated.

**Learning / practice:**

- Map a developer workflow from repository creation through first successful build/deploy.
- Identify friction and measure a baseline (setup time, queue time, failed build rate, support tickets, or manual steps).
- Improve one high-friction step and measure adoption or time saved.
- Write usable docs/runbooks and gather feedback from actual users.

**Evidence to add only after validating:** onboarding/setup time reduced, teams adopting a workflow, support burden reduced, queue time improved, or fewer manual interventions.

## Priority 5: Practice technical leadership without overstating authority

**Why:** Senior roles often require influencing peers and stakeholders, even for individual contributors. Your AI platform work already provides evidence of technical ownership and stakeholder coordination. Make that a practiced, repeatable skill.

**Learning / practice:**

- Write short architecture decision records for important tradeoffs.
- Practice concise project updates: user need, options, recommendation, risks, decisions needed, outcome.
- Seek opportunities to review designs, coach on tooling, or coordinate a bounded cross-team improvement.
- Separate “I decided/implemented/operated” from “the team decided/delivered.”

**Evidence to add only after it happens:** a decision adopted, a cross-team change delivered, engineers unblocked, or a standard/runbook adopted.

## Lower priority unless job descriptions demand it

- **Backstage/internal developer portal:** useful for platform-specific jobs but not required to validate senior DevOps ability. Consider only if target postings repeatedly ask for IDP ownership.
- **Deep EKS fleet administration / service mesh:** substantial investment; prioritize only if seeking cluster-platform roles and willing to own that operational domain.
- **Certifications:** pursue only when they help pass a specific employer or recruiter filter. A working project and clear operational reasoning are more useful for many teams.
- **New languages/frameworks:** do not chase Go, Rust, or AI tooling just because they appear in reference CVs. Your differentiator is infrastructure delivery and ownership.

## 90-day sequence (adjust to job-search time)

1. **Weeks 1–2: Role calibration.** Save 10–15 real job descriptions you would accept. Tag requirements as demonstrated, adjacent, or genuine gap. Note on-call, infrastructure ownership, team size, salary, and domain.
2. **Weeks 2–5: Reliability exercise.** Pick one workload, define SLI/SLO, create runbook and alerts, run a failure exercise, and write the postmortem.
3. **Weeks 4–8: AWS depth project.** Build a small but production-shaped Terraform deployment; test restore, IAM boundaries, networking, observability, and cost.
4. **Weeks 7–10: Platform workflow improvement.** Improve one developer workflow and gather measurements or user feedback.
5. **Weeks 10–12: Interview practice and reassessment.** Practice architecture and incident scenarios; use recruiter/interview feedback to update the gap list. Keep applying throughout rather than waiting for all projects to finish.

## Guardrails for choosing a role

During interviews, ask:

- Who owns AWS accounts, networking, Kubernetes clusters, security, and production incidents today?
- What would I personally own in the first 90 days, and what support exists?
- How large is the platform/DevOps team, and what expertise is available from peers?
- What is the on-call rotation and incident escalation path?
- Is the role primarily building shared tooling, operating an established platform, or being the only infrastructure engineer?
- What reliability, delivery, or cost problems would success improve?

Roles with team support and bounded platform ownership are likely a better stretch than roles expecting one person to own every cloud, cluster, security, and on-call function immediately. Compensation and company interest should be weighed alongside the actual support and authority attached to the responsibility.

## What to track

Keep a lightweight evidence log with date, system, context, personal contribution, collaborators, baseline, outcome, and proof/source. This supplies accurate CV bullets and interview stories, and helps distinguish genuine growth from keyword accumulation.
