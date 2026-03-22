# Cornell DTI × ServiceNow — Project Dashboard

**Live site:** https://nishtobehonest.github.io/dti-servicenow-dashboard/

A single-page research dashboard for the Cornell DTI × ServiceNow Spring 2026 consulting engagement. Built as a stakeholder-facing artifact to track deliverables, surface findings, and communicate strategic recommendations to the client (Sridhar Ravichandran, AppEngine BU).

---

## What's inside

The dashboard has six tabs:

| Tab | Contents |
|-----|----------|
| **Overview** | Project status, deliverable tracker, team info, and weekly progress |
| **Journey Map** | End-to-end ServiceNow developer journey across No-Code / Low-Code / Pro-Code user types |
| **Analysis** | Key findings from primary and secondary research, confidence levels, and validation roadmap |
| **BAP Framework** | Business Adoption Plan — Activation → Retention → Graduation framework with observable signals |
| **Competitive** | Competitive landscape analysis (Lovable, Replit, Bolt.new, Power Apps, Mendix) |
| **Ecosystem Map** | ServiceNow App Engine ecosystem — AES, Creator Studio, Build Agent, PDI, AEMC, AEU |

---

## Project context

Cornell DTI is partnering with ServiceNow to understand why developers drop off between building a first app and deploying a production-ready app — and to recommend fixes.

**Team:** Nishchay, Michelle, Jenny, Yani
**Timeline:** Feb–May 2026
**Midpoint presentation:** Mar 24–26 · **Final presentation:** May 11–13

---

## Updating the dashboard

The source file lives in the private research repo. To push an update:

```bash
cp /path/to/outputs/dashboard.html /tmp/dti-servicenow-dashboard/index.html
cd /tmp/dti-servicenow-dashboard
git add index.html
git commit -m "Update: dashboard [describe change]"
git push
```

GitHub Pages redeploys automatically within ~1 minute.
