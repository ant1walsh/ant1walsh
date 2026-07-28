Anthony Walsh
I’m a technical product marketer with 10 years of experience directing go-to-market strategy for 16 AI infrastructure and applications solutions that generated over $120 million for pre-IPO startups and Fortune 50 enterprises like Meta. 


Currently, I’m developing AI agents for market research and content automation as Marketing Director for Applied AI at Demodoc, a GTM engineering studio. I’ve been nominated as an AI Adoption Fellow with the Ethical AI Governance Group and an exhibitor at the Agentic AI Summit hosted by UC Berkeley.
Open-Source Agents
Repo
	What it does
	Stack
	ICP-and-Persona-Analyzer
	Segments an uploaded customer list into firmographic distributions, or builds buyer and user personas — responsibilities, KPIs, challenges, tech stack, engagement channels, and the questions each persona asks at every stage of the customer journey
	n8n · Gemini 3.1 Pro · Gmail
	Product-Positioning-Generator
	Turns form inputs and an optional product spec into a tagline, positioning statement, and value proposition — or a feature release note. Enforces a banned-words list so the copy reads like a person wrote it
	n8n · Gemini 3.1 Pro · Gmail
	Customer-Story-Generator
	Transcribes a recorded customer interview, then writes the case study and matching LinkedIn and X posts. Honors stated privacy permissions and anonymizes personally identifiable information (PII) by default
	n8n · Gemini 3 Flash + 3.1 Pro · Gmail
	

Two Python agents run daily in production at Demodoc — one ranking buying signals from developer communities, one filtering competitor news into a verified brief. Those repos are private for now; the design notes behind them are on anthony-walsh.com/ai-agents.
Elsewhere
* Website — anthony-walsh.com
* LinkedIn — https://linkedin.com/in/anthonyrwalsh 


If you're building GTM tooling, I'd like to compare notes. One question I keep turning over: how much of a research agent's scoring belongs in the model versus in hard-coded rules? I've landed on rules for anything a sales team acts on — the acceptance criteria have to be auditable — but I continue asking myself whether the trade-off is settled…