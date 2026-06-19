# Atlas Controls, Privacy, and Limitations

## How is Atlas kept under control?

Atlas solutions can use defined tools, fixed permissions, approved knowledge sources, validation,
rate limits, timeouts, monitoring, and human review. High-impact actions should require appropriate
authorization or confirmation.

Atlas should not be given arbitrary code execution, unrestricted web browsing, or open-ended access to
business systems.

## What does the public Atlas website demo do?

The public website demo can:

- Hold a spoken conversation about Omniscient AI
- Answer from approved Omniscient AI knowledge
- Show approved website links
- Navigate to an approved internal page after explicit visitor confirmation
- Allow the visitor to interrupt, mute, or end the session

## What does the public demo not do?

The public website demo does not:

- Act as a general-purpose assistant
- Browse arbitrary websites
- Execute arbitrary code or tools
- Submit forms or send messages
- Make purchases
- Book appointments
- Change authentication settings
- Navigate to arbitrary external destinations

## Does the public demo store audio or transcripts?

The MVP is designed not to persist raw visitor audio or full or partial conversation transcripts.
Conversation state is kept only for the active session and discarded when the session ends.

Operational telemetry may include non-content metadata such as generated session identifiers, timestamps,
duration, turn count, latency, error codes, action types, usage, and estimated cost.

## Should visitors share personal or sensitive information?

No. Visitors should not provide passwords, credentials, payment details, private records, confidential
business data, or unnecessary personal information to the public demo.

## Can Atlas make mistakes?

Yes. AI systems can misunderstand speech, retrieve the wrong passage, or produce an incomplete answer.
Atlas should use approved knowledge, acknowledge uncertainty, and escalate or direct the visitor to the
contact page when the available information does not support an answer.

## Does Atlas replace human support teams?

Atlas is designed to automate common work and support faster handling while preserving human escalation
for complex, sensitive, ambiguous, or high-impact cases. The appropriate balance between automation and
human review depends on the workflow.
