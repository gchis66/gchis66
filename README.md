### Hi, I'm Greg.

I'm an AI engineer in South Florida. I was a web developer for 8 years, and for the last two I've been building apps on top of LLMs and hosting them on AWS and Vercel. Everything below is live, so click around.

**AWS Solutions Architect Associate** · **HashiCorp Terraform Associate** · **Google Cloud Associate Cloud Engineer**

#### Things I built that you can use right now

| Project | What it does | Proof |
|---|---|---|
| [Voice agent](https://gregorychisholm.com/talk) · [code](https://github.com/gchis66/portfolio-site) | Talk to an AI about my work, in your browser. Answers come only from a 109-chunk knowledge base, and it says so when it has no source. | No API key ever reaches the browser. Kill switch, rate limits and a pre-charged daily spend ceiling. About half a cent per turn. [Threat model](https://gregorychisholm.com/talk/architecture) |
| [Legal PDF extractor](https://legal-pdf-extract.vercel.app) · [code](https://github.com/gchis66/legal-pdf-extract) | Contracts in, 26 fields and clause risk flags out. Every flag cites the clause it came from. | Code verifies each quote exists in the source document. 14 of 14 fields correct against attorney annotations (CUAD). |
| [Press release monitor](https://press-monitor-ten.vercel.app) · [code](https://github.com/gchis66/press-monitor) | Watches company newsrooms and emails a summary when something new is published. | Three-tier pipeline cut projected API cost from $749 to $99 a month at 118,800 checks. 92 of 92 live checks pass against production. |
| [Receipt to CSV](https://receipt-to-csv-nine.vercel.app) · [code](https://github.com/gchis66/receipt-to-csv) | Receipt photos and PDFs in, accountant-ready CSV out, with a review step before export. | Benchmarked five vision models. The cheapest was the most accurate (15 of 15 fields), about 19x cheaper than the priciest. |

#### How I work
AI-first, every day: Claude Code and coding agents write most of the first draft, I write the spec and review every line. Stack I reach for: TypeScript and Node, Next.js, Python for scripts and data work, AWS Lambda, API Gateway, DynamoDB, S3, CloudFront, IAM, Terraform, GitHub Actions with OIDC.

#### Open to
Contract and full-time AI engineering work, remote (US). [gregorychisholm.com](https://gregorychisholm.com) · [LinkedIn](https://www.linkedin.com/in/gregory-chisholm1/)
