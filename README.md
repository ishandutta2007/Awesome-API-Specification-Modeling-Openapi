# Awesome-API-Specification-Modeling-Openapi

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.

I also have to flag what the search results actually support, because **two of your listed tools are dead or deprecated**, and several entries have no usable pricing.

## Critical findings

**Apicurio Studio is fully deprecated.** As of October 23, 2025, the Apicurio team announced Studio is deprecated; its editing capabilities were folded into **Apicurio Registry 3.1.0** as an opt-in "Drafts" feature . **Do not list Apicurio Studio as a live product.** List Apicurio Registry instead.

**Apiary is shutting down.** Oracle terminated support, with service end expected around **September 2026** . **Do not list it as a current option.**

**RepreZen API Studio has no usable data.** SourceForge returned only a fragment ("Starting Price: $0") , with no feature detail, no star count, and no confirmation the product is actively maintained. **Mark as "data not surfaced" or omit.**

## What the search results actually contain

**Open-source projects (usable):**

| Project | License | Stars | Notes |
|---|---|---|---|
| **OpenAPI Generator** | Apache 2.0 | **~27,000** | v7.25.0 (Aug 2026); covers many languages and server stubs  |
| **TypeSpec** | Open source (Microsoft) | **~5,902** | Language for defining cloud APIs; generates multiple description formats, client code, and docs  |

**Proprietary pricing (usable):**
- **Stoplight**: Basic **$44/month annual** ($56 monthly) for 3 users; Startup **$113/month annual** for 8 users; Pro Team **$362/month annual** for 15 users . No end-of-life announcement as of September 2026 .
- **Redocly**: Pro **$249/month annual** ($2,988/yr, 3 projects); Scale **$729/month annual** ($8,748/yr, 10 projects); Enterprise custom .
- **Fern**: Free tier with Python/TypeScript SDKs; Enterprise custom per SDK . Postman Team eligibility gives **Free (a $250/mo value)** with 25 members and 2,500 pages .
- **SwaggerHub**: Software Advice lists **starting at $64.80/month** , but no plan detail beyond that.
- **Postman**: **$12/user/month** starting price .

**What is missing:**
- **No pricing** for Postman API Definition Creation (as a distinct feature), Apicurio Registry, or RepreZen.
- **No star counts** for Redocly, SwaggerHub, Stoplight, or Fern (all proprietary).
- **No revenue or valuation** for any vendor.
- **No confirmation** that RepreZen is actively maintained.

## What I recommend

**Remove Apicurio Studio and Apiary entirely.** Both are dead or dying . If you want an Apicurio entry, list **Apicurio Registry 3.1.0** (open source, Apache 2.0) with the "Drafts" editing feature .

**The open-source section is strong but narrow:**
- **OpenAPI Generator** (~27k stars) 
- **TypeSpec** (~5.9k stars) 
- **Apicurio Registry** (Apache 2.0, replaces Studio) 

**The SaaS section has usable pricing for Stoplight, Redocly, Fern, SwaggerHub, and Postman.** Mark RepreZen as **"data not surfaced"** or omit it.

If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not list Apicurio Studio or Apiary as live, fabricate RepreZen pricing, or invent star counts for proprietary tools.
