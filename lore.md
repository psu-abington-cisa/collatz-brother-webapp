# Collatz & Brother

## The Ledger Incident

For almost ninety years, **Collatz & Brother** had been one of the most respected private financial firms on the East Coast.

The company began in 1937 as a small investment office serving local businesses. Over the decades, it grew into a sophisticated financial services company managing private wealth, corporate accounts, investment portfolios, and confidential financial records for some of the region's most influential families.

The firm's reputation was built on one principle:

**Trust is the most valuable asset we manage.**

By 2026, Collatz & Brother had expanded far beyond its original offices. Its employees worked across several departments, clients managed accounts through an online portal, and an aging collection of internal systems quietly supported the company's modern infrastructure.

On the outside, everything looked healthy.

Inside, things were different.

---

## The People Behind the Firm

**Bernard Collatz II**, the company's president, was the public face of Collatz & Brother.

Bernard inherited the company from his family and transformed it into a modern financial institution. He was intelligent, ambitious, and obsessed with protecting the firm's reputation.

To Bernard, bad news was dangerous.

A missed investment was a problem.

An unhappy client was a problem.

A security incident was a catastrophe.

He believed most problems could be solved by keeping them quiet long enough to fix them.

That philosophy shaped the company.

---

**Sophie Collatz**, Bernard's daughter, was the firm's Chief Operating Officer.

She was responsible for keeping the company running.

Client onboarding.

Internal administration.

Employee accounts.

Financial documents.

Vendor relationships.

When something broke, Sophie usually knew about it before anyone else.

She also knew where almost everything was stored.

Her greatest weakness was the same thing that made her good at her job:

She trusted people.

---

**Francis Collatz**, Bernard's older brother, served as the company's Chief Financial Officer.

Francis was old-school.

He still preferred physical ledgers, signed approval forms, and conversations in person.

He distrusted new technology but tolerated it because the rest of the company demanded it.

Francis kept several confidential spreadsheets containing information that was never supposed to leave the finance department.

Investment schedules.

Wire instructions.

Client balances.

Internal forecasts.

He believed those files were safe because only a handful of people knew they existed.

---

**Lucien Collatz** was responsible for technology.

Officially, he was the company's Director of Information Systems.

In practice, Lucien was the person everyone called when something technical went wrong.

He had inherited dozens of systems that had been built at different points throughout the company's history.

Some were modern.

Some were patched together.

Some had been forgotten entirely.

Lucien kept telling management that the infrastructure needed to be rebuilt.

Management kept telling him:

**"Next quarter."**

---

The firm also employed two outside consultants.

**Emilien Dupont** was a systems engineer brought in to modernize several internal applications.

He was brilliant, impatient, and convinced that every old system had a weakness somewhere.

**Marie Dupont**, his sister, worked as a compliance consultant.

Marie had spent months warning the company about access controls, outdated accounts, exposed documents, and poor separation between internal and public systems.

She maintained a binder full of unresolved security findings.

Most of them had been marked:

**LOW PRIORITY**

---

# The Problem

The incident started with something small.

A former employee's account was still active.

Nobody noticed because the employee had left months earlier.

The account still had access to an internal document system.

The document system was connected to several of the firm's web applications.

Nobody considered the connection important.

Then someone noticed that a confidential document had been accessed after business hours.

The file contained information about an upcoming acquisition.

Nothing was stolen.

At least, nothing anyone could prove.

Bernard ordered Lucien to investigate quietly.

"No regulators," Bernard said.

"No lawyers."

"And absolutely no clients."

Lucien began reviewing the logs.

The logs were incomplete.

Several systems did not retain them.

Some accounts had no meaningful audit trail.

One server was still running software that had not been properly updated in years.

Lucien found something worse.

The company's public website could communicate with an internal service that was never intended to be exposed externally.

He immediately shut it down.

The website went offline for twelve minutes.

Bernard demanded an explanation.

Lucien gave him one.

"The problem isn't the website."

Bernard stared at him.

"Then what is it?"

Lucien looked back at the server.

"The problem is that we don't know what else is connected to it."

---

# The Investigation

The board authorized a controlled penetration test.

The test was supposed to be straightforward.

Find the obvious vulnerabilities.

Document them.

Fix them.

Close the report.

Instead, the security testers discovered that the public-facing website was connected to far more of the company than anyone realized.

Public pages revealed internal naming conventions.

Old files exposed employee information.

Forgotten directories contained documents that were never meant to be public.

A legacy application accepted requests it should have rejected.

An administrative portal behaved differently depending on how a user reached it.

Several accounts appeared to have permissions far beyond what their owners needed.

Piece by piece, the testers began reconstructing the company's internal architecture.

The deeper they went, the stranger the story became.

Every vulnerability led somewhere.

Every system appeared to trust another system.

Every shortcut created years earlier had become part of a much larger chain.

---

# The Missing $4.7 Million

Then the testers found the transaction logs.

One account had been repeatedly accessing a restricted financial system.

The account belonged to a contractor.

The contractor claimed he had never used it.

The activity appeared to originate from inside the company.

The transfers were not obvious thefts.

They were small.

Carefully timed.

Spread across several accounts.

Someone had been moving money through the firm's systems without triggering the normal alerts.

The total amount was eventually calculated:

**$4.7 million.**

Bernard refused to believe it.

Francis demanded the transaction records.

Sophie began calling department heads.

Lucien stopped talking.

Because he had just realized something.

The financial system had not been breached recently.

The attacker had probably been inside the environment for months.

Possibly longer.

---

# The Insider

The investigation narrowed the possibilities.

Only a small number of people had access to the systems involved.

Bernard.

Francis.

Sophie.

Lucien.

Emilien.

Marie.

And several employees whose credentials appeared in the logs.

Everyone became a suspect.

The family began turning against itself.

Francis accused Sophie of giving too many people access.

Sophie accused Lucien of ignoring his own security warnings.

Lucien accused Bernard of refusing to fund the upgrades.

Bernard accused everyone of failing to protect the firm.

Then Marie found something in her compliance records.

An old warning.

Buried in an audit from two years earlier.

It described a service account with excessive privileges.

The account had never been removed.

Its password had never been changed.

And the account could access systems that had nothing to do with its original purpose.

The account was still active.

---

# The Real Threat

The testers eventually used the same path an attacker could have used.

They moved from the public website into an internal application.

From there, they discovered an administrative account.

That account could access internal documents.

Those documents exposed credentials.

The credentials opened another system.

That system exposed financial records.

And the financial records revealed the attacker's trail.

The company had not been protected by a secure architecture.

It had been protected by obscurity.

And obscurity had failed.

---

# The Final Discovery

The $4.7 million had not disappeared.

It had been moved into accounts controlled by a shell company.

The shell company was connected to a former executive.

A person who had left Collatz & Brother nearly a year earlier.

Someone whose account was still active.

Someone whose credentials had never been revoked.

Someone who had retained access to internal systems after leaving the company.

The breach had started with something embarrassingly simple.

An account nobody remembered to disable.

Everything else came afterward.

---

# The Aftermath

The company survived.

But it changed.

Bernard resigned as president.

Francis ordered a complete financial audit.

Sophie rebuilt the company's internal processes.

Lucien replaced the oldest systems.

Marie finally emptied her binder of unresolved security findings.

Emilien was given permission to rebuild the systems he had been warning about for years.

The company also published a new statement on its website.

It contained only one sentence:

**"Trust must be earned continuously."**

The public never learned how close Collatz & Brother had come to collapse.

But inside the company, everyone understood what had happened.

The attackers had not defeated a sophisticated financial institution.

They had simply followed the doors the company had accidentally left open.

And once they found the first door, every other door became easier to find.
