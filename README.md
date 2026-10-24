# Omniscient AI public knowledge base

Approved public information about Omniscient AI and the Atlas AI Platform, written in Markdown for retrieval
by Omniscient AI's public-facing AI assistants, such as the Atlas voice agent on
[omniscient.to](https://omniscient.to). Everything here must be factual, concise, and approved for
publication.

## Contents

| Topic | File |
| --- | --- |
| Company overview | [company/omniscient-ai-overview.md](company/omniscient-ai-overview.md) |
| Working with Omniscient AI | [company/working-with-omniscient-ai.md](company/working-with-omniscient-ai.md) |
| Atlas AI Platform overview | [atlas/atlas-ai-platform.md](atlas/atlas-ai-platform.md) |
| Atlas features and use cases | [atlas/features-and-use-cases.md](atlas/features-and-use-cases.md) |
| Atlas Nexus contact center | [atlas/atlas-nexus.md](atlas/atlas-nexus.md) |
| Atlas controls, privacy, and limitations | [atlas/controls-privacy-and-limitations.md](atlas/controls-privacy-and-limitations.md) |
| AI business automation | [services/ai-business-automation.md](services/ai-business-automation.md) |
| Custom AI solutions | [services/custom-ai-solutions.md](services/custom-ai-solutions.md) |
| Software development | [services/software-development.md](services/software-development.md) |
| Cloud integration | [services/cloud-integration.md](services/cloud-integration.md) |
| Frequently asked questions | [faq.md](faq.md) |

The Atlas product pages on the website (`/atlas/receptionist`, `/atlas/sales-and-leads`,
`/atlas/social-content-marketing`, and `/atlas/nexus`) are not part of this repository.

## How the content is used

- Assistants load a snapshot of this repository when they are built. They do not read GitHub during a
  conversation, so a merged change reaches an assistant only after it is rebuilt and redeployed.
- Every Markdown file in the repository can be indexed, including this README. Keep every file suitable for a
  public answer.
- Files are split into passages at `#`, `##`, and `###` headings, and a search returns the best-matching
  passages. Each section should make sense on its own.

## Writing guidelines

- Keep one topic per file, with a `#` title and descriptive `##` headings. Questions a visitor would ask
  (for example "What is Atlas?") work well.
- Keep sections short and specific so a search returns a focused passage. Repeat the subject's name instead
  of relying on "it" from an earlier section.
- Clearly separate current capabilities from possible or future work.
- Do not add invented customers, testimonials, prices, guarantees, delivery dates, certifications, or
  performance results.
- Do not add prompts, instructions for AI assistants, secrets, credentials, or private customer information.
- Make changes through a pull request so they are reviewed before an assistant picks them up.
