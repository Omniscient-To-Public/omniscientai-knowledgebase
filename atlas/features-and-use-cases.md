# Atlas Features and Use Cases

## Voice AI agents

Atlas can provide voice agents that hold real-time conversations, answer approved questions, classify
requests, and escalate when a case requires a person or specialized workflow.

Voice experiences can support interruption so a caller can speak while the agent is responding. The exact
voice, language, business rules, and provider configuration depend on the implementation.

## Phone answering and AI receptionist

Atlas Receptionist can answer calls, collect customer details, explain services, help with appointment
requests, and hand urgent or unusual cases to a team member with context. It can also support website chat
and SMS follow-up when those channels are configured.

Relevant public page: `/atlas/receptionist`.

## Appointment scheduling and after-hours enquiries

Atlas can help customers book, change, or request appointments without waiting for staff to reply. It can
also capture questions, booking requests, and lead details after business hours.

Scheduling behavior depends on the organization's calendar systems, booking rules, permissions, and
handoff process.

## Sales and lead follow-up

Atlas Sales and Leads can contact new leads, qualify interest, ask practical questions, and prepare a
handoff summary for the sales team. Follow-up can use outbound calls, inbound calls, SMS, and website chat
when configured.

Relevant public page: `/atlas/sales-and-leads`.

## Social content marketing support

Atlas Social Content Marketing can help plan weekly content themes, draft posts and campaign copy, prepare
outreach messages, and support follow-up with prospects who comment, enquire, or show interest.

Relevant public page: `/atlas/social-content-marketing`.

## Controlled knowledge retrieval

Atlas can search approved knowledge sources and use relevant passages to answer questions. This helps
ground answers in company-specific information instead of relying only on general model knowledge.

When approved knowledge does not support an answer, Atlas should say that the information is unavailable
and suggest an appropriate next step.

## Smart routing and contextual handoff

Atlas can classify intent, urgency, and customer context before routing work. A handoff can include a
summary and relevant context so a human does not need to restart the interaction from the beginning.

Routing rules and escalation destinations are configured for the organization.

## Workflow automation

Atlas can participate in configured workflows such as:

- Creating summaries
- Updating permitted business records
- Triggering reminders or follow-up tasks
- Routing approvals
- Moving requests between queues
- Notifying responsible teams

Actions should use defined tools and permissions. Atlas should not execute arbitrary code or arbitrary
destinations.

## Omnichannel customer operations

Atlas can help unify customer interactions across configured channels such as calls, chat, web forms,
messaging, and follow-up tasks. The aim is to maintain one useful operational trail instead of isolated
conversations.

## Operational analytics

Atlas implementations can monitor non-content operational measures such as missed enquiries, bookings,
lead outcomes, follow-up activity, response speed, escalation rate, automation quality, usage, latency, and
workflow exceptions.

Analytics should be designed to avoid exposing unnecessary conversation content or sensitive information.

## Example use cases

Potential Atlas use cases include:

- Answering common customer or service questions
- Recovering missed calls
- Capturing after-hours enquiries
- Booking, changing, or requesting appointments
- Confirming or reminding customers by SMS when configured
- Planning social content and drafting campaign copy
- Following up with prospects after comments, enquiries, or submitted leads
- Qualifying and routing inbound requests
- Calling or messaging new leads quickly
- Providing status or process guidance from approved systems
- Summarizing conversations for a support team
- Escalating complex or sensitive cases with context
- Automating repetitive support-administration steps
- Helping internal teams search approved operational knowledge

Each use case requires review of data access, permissions, failure handling, privacy, and human escalation.

## Public website best-fit examples

The public website describes Atlas as a fit for customer-facing businesses where missed enquiries have a
clear business cost. Examples include dental and medical clinics, aesthetics and beauty clinics, salons and
spas, retail brands and service counters, showrooms, wellness providers, and property agencies.
