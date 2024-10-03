# CRS is an umbrella project

```mermaid
mindmap
  root((CRS))
    id[Rules]
      Creation
      Maintenance
      Plugins
    id[Release]
      Changelog
      Release procedure
      Backporting
    id[Security]
      Security tracker
      Triaging reports
    id[Tools]
      crs-toolchain
        regex-assembly
      go-ftw
      albedo
      Parser
        secrules_parsing
        seclang antlr
        msc_pyparser
      Linter
        rules-check (msc_pyparser based)
    id[Dev-On-Duty]
      Slack
      GH Issues
      StackOverflow
      Twitter/X
    id[Testing]
      Rules Testing
      Testing Schema
      Quantitative
      Performance
      DoS Testing
    id[Infrastructure]
      Updates (renovatebot)
      GitHub Actions
      Containers
        modsecurity-crs-docker
          apache
          nginx
          openresty
        coraza-crs-docker
      Sandbox
        AWS Infra
        OpenResty Frontend
        Challenges
        Docker Compose
    id[Project]
      Bi-Monthly meetings
      Developer Engagement
      Reimbursements
    id[Documentation]
      Website Blogs (coreruleset.org)
      Documentation (coreruleset.org/docs)
      OWASP Website (owasp.org/www-project-modsecurity-core-rule-set)
      Meeting archives
    id[Community Relationship]
      Sponsors
      Engines
      OWASP Projects
      OWASP HQ
    id[Retreat]
      Projects
      Knowledge Transfer
      Team Activities
    id[Public Relations]
      Blog Posts
      Social Media
    id[Research]
      CVEs (Seaweed)
      Status Page
      Payloads
      Evasions
```
