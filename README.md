<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A66C2,100:2F81F7&height=180&section=header&text=Kristijan%20Plaushku&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Software%20Architect%20%7C%20Technical%20Lead&descSize=18&descAlignY=55" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=800&color=2F81F7&center=true&vCenter=true&width=600&lines=Software+Architecture+for+Startups+%26+Enterprise;Test+Automation+%26+Quality+Engineering;LLM+Integration+in+SaaS+%26+Test+Automation;Performance+Testing+at+Scale" alt="Typing SVG" />

<br/>

[![Email](https://img.shields.io/badge/Email-info%40plaushkusolutions.com-0A66C2?style=for-the-badge&logo=gmail&logoColor=white)](mailto:info@plaushkusolutions.com)

</div>

## About Me

Software Architect with 5+ years of experience delivering enterprise and startup software, QA transformation, and AI enabled solutions across international projects.

I design scalable architectures and build custom software, test automation frameworks, and performance testing strategies. I lead teams across the full software lifecycle, from requirements to production delivery.

Curious by nature: I like taking technologies apart to understand how they work, and I am always exploring new tools, languages, and ideas.

```text
Architecture      Scalable systems for startups and enterprise
Automation        AI assisted test automation for web and mobile
Performance       Load testing and scalability validation
Infrastructure    Cloud (AWS, GCP, Azure) and on premise environments
DevOps            CI/CD quality gates and release validation
```

<br/>

## Tech Stack

<div align="center">

**Languages & Frameworks**

<img src="https://skillicons.dev/icons?i=java,py,cs,ts&theme=light" alt="Languages" />

**Automation & Testing**

<img src="https://skillicons.dev/icons?i=selenium,postman&theme=light" alt="Testing" />
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" alt="Playwright" />
<img src="https://img.shields.io/badge/Robot%20Framework-000000?style=for-the-badge&logo=robotframework&logoColor=white" alt="Robot Framework" />
<img src="https://img.shields.io/badge/Appium-663399?style=for-the-badge" alt="Appium" />
<img src="https://img.shields.io/badge/JMeter-D22128?style=for-the-badge&logo=apachejmeter&logoColor=white" alt="JMeter" />

**Infrastructure, DevOps & Data**

<img src="https://skillicons.dev/icons?i=docker,kubernetes,jenkins,githubactions,aws,gcp,azure,mysql,postgres&theme=light" alt="Cloud and DevOps" />

</div>

<br/>

## How I Work

```mermaid
flowchart LR
    A([Software<br/>Architecture]) --> B[Tailored<br/>Development]
    A --> C[Test<br/>Automation]
    A --> D[Performance<br/>Testing]
    A --> E[Infrastructure &<br/>DevOps]

    B --> B1[Java · Python · C# · TypeScript<br/>RESTful APIs · Microservices]
    C --> C1[Selenium · Playwright · Appium<br/>Robot Framework · BrowserStack]
    D --> D1[JMeter · Load Testing<br/>Bottleneck Analysis]
    E --> E1[Docker · Kubernetes · Jenkins · GitHub Actions<br/>AWS · GCP · Azure · On Premise]

    style A fill:#0A66C2,stroke:#0A66C2,color:#fff
```

<br/>

## AI Engineering

I integrate LLMs into SaaS products and test automation pipelines. Concrete work, not demos:

**Agents & LLM chaining**

- Multi step agent workflows with tool calling: typed tool schemas, bounded execution loops, state persisted between steps, deterministic fallbacks when model output fails validation
- Chained LLM calls where each step's output is schema validated and transformed before feeding the next, with checkpointing so a failed step retries without rerunning the whole chain

**RAG pipelines**

- Retrieval pipelines end to end: chunking strategies tuned per content type, embedding generation, vector store indexing, hybrid retrieval combining vector and keyword search, reranking before context assembly
- Retrieved context scored and truncated to a fixed token budget instead of stuffing the window

**Fine tuning & model selection**

- Dataset curation and formatting for supervised fine tuning, with train/validation splits and comparison against few shot baselines before committing to a tuned model
- Model routing: small models for classification and extraction, larger models only where the eval data shows reasoning depth matters

**Evals & cost management**

- Fixed eval sets versioned with the prompts, run as regression gates in CI before every prompt or model change
- Token and latency budgets enforced per endpoint, usage metering per tenant, response caching for repeated prompts

**LLM integration in SaaS products**

- Model API orchestration with structured output: JSON schema constrained responses, parse and validation layer, typed errors on malformed output
- Retry, timeout, and fallback policies across providers and model versions
- Prompt versioning treated like code: tracked in git, reviewed, and regression tested like any other change

**Coverage expansion in test automation**

- Test case generation from requirements and OpenAPI specifications, including negative paths, boundary values, and invalid payloads
- Generated cases deduplicated against the existing suite and traced back to requirements, so coverage gain is measured, not assumed

<br/>

## Technical Expertise

| Area | Technologies |
|---|---|
| **Languages** | Java, Python, C#, TypeScript |
| **Test Automation** | Selenium, Selenide, Robot Framework, Playwright, Appium, BrowserStack |
| **Performance** | JMeter, load testing, scalability analysis, bottleneck detection |
| **API & Integration** | RESTful APIs, Postman, Pact, contract testing |
| **Infrastructure & DevOps** | Docker, Kubernetes, Jenkins, GitHub Actions, Azure DevOps, AWS, GCP, Azure, on premise environments |
| **Databases** | MySQL, PostgreSQL, Oracle DB |
| **Enterprise** | SAP Hybris, SAP CX, microservices architecture |
| **Security** | Burp Suite |
| **QA Management** | Test strategy, release management, defect management, Jira, Atlassian |

<br/>

## Featured Work

<table>
<tr>
<td width="50%" valign="top">

### AI Self Healing Automation

Architected and shipped a self healing mechanism for Robot Framework: locator failures are intercepted at runtime through the listener interface, the DOM subtree at the failure point is serialized within a fixed token budget, an LLM generates candidate selectors, each candidate is validated against the live page, and healed locators are emitted as reviewable diffs for version control.

</td>
<td width="50%" valign="top">

### Enterprise QA Transformation

Led automation and QA initiatives across international enterprise projects: e-commerce, public administration, mobile apps, and performance critical platforms.

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### Training & Mentorship

Instructor for the RPA and Web Automation module at ITS Talent Factory. Delivered a 16 hour in person course on coding, automation, and practical engineering.

</td>
</tr>
</table>

<br/>

## Certifications & Memberships

![ISTQB](https://img.shields.io/badge/ISTQB-Certified_Tester_Foundation_Level-0A66C2?style=flat-square)
![Robot Framework](https://img.shields.io/badge/Robot_Framework-Foundation_Member-000000?style=flat-square&logo=robotframework&logoColor=white)
![Erasmus](https://img.shields.io/badge/Erasmus_for_Young_Entrepreneurs-Berlin_Mentorship-2F81F7?style=flat-square)

<br/>

## Current Focus

- Software architecture for startup and enterprise applications
- Tailored development for business critical platforms
- AI assisted test automation
- Performance testing and scalability validation
- Staying curious: exploring new tools, AI technologies, and better ways to build software

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2F81F7,100:0A66C2&height=100&section=footer" width="100%"/>

</div>
