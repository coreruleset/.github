# CRS is an umbrella project

```mermaid
mindmap
  root((CRS))
    id[Rules]
      Creation
      Maintenance
      id[Releasing]
        Changelog
        Release process
        Backporting
      Plugins
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
	  Twitter
    id[Testing]
      Rules Testing
      Testing Schema
      Quantitative
      Performance
	  DoS testing
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
    id[Security]
      Security tracker
      Triaging reports
    id[Project]
      2 Monthly meetings
      Developer Engagement
      Meeting archive
	  Reimbursements
    id[Documentation]
      Website Blogs (coreruleset.org)
      Documentation (coreruleset.org/docs)
      OWASP Website (owasp.org/www-project-modsecurity-core-rule-set)
    id[Community Relationship]
      Sponsors
      Engines
      OWASP Projects
      OWASP HQ
    id[Public Relations]
	  Blog Posts
	  Social Media
    id[Retreat]
      Projects
      Knowledge Transfer
      Team Activities
    id[Research]
      CVEs (Seaweed)
      Status Page
      Payloads
      Evasions
```
