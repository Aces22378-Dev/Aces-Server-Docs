# QA HANDBOOK

**Author:** Its-Aurelia-Dev
**Server Staff Document — QA Team**

## 1. PURPOSE

The Quality Assurance (QA) Team is responsible for testing server systems, identifying bugs, verifying fixes, and helping ensure that new features work correctly before they reach the wider community.

QA staff are not primarily moderators or developers. Their role is to **find, document, reproduce, and verify problems**.

---

# 2. QA RESPONSIBILITIES

QA staff are responsible for:

* Testing new features.
* Testing bug fixes.
* Finding bugs and unexpected behavior.
* Reproducing reported issues.
* Creating clear bug reports.
* Regression testing.
* Testing permissions and access controls.
* Testing server features from a user perspective.
* Verifying that fixes actually resolve reported issues.
* Reporting serious problems to Developers and Admins.
* Maintaining confidentiality around unreleased features.

---

# 3. QA PRINCIPLES

### Be Thorough

Do not assume something works simply because it works once.

Test normal, unusual, and incorrect inputs where appropriate.

### Be Objective

Report what actually happened rather than what you expected to happen.

### Be Reproducible

A Developer should be able to understand how you encountered the problem.

### Be Responsible

Do not intentionally damage production systems while testing.

### Be Confidential

Unreleased features, vulnerabilities, internal tools, and private test information should remain confidential.

---

# 4. TESTING ENVIRONMENTS

Testing should preferably happen in a designated development or testing environment.

QA staff should not use production for risky experiments.

Production testing should only occur when:

* The test is approved.
* The risk is understood.
* There is no reasonable alternative.
* The test will not negatively affect members.

---

# 5. BUG REPORTING

A good bug report should include:

**Title:**
Short description of the problem.

**Expected behavior:**
What should happen.

**Actual behavior:**
What happened instead.

**Steps to reproduce:**
Safe and accurate reproduction steps.

**Affected system:**
The feature, bot, website, command, or other system affected.

**Severity:**
Low / Medium / High / Critical.

**Evidence:**
Screenshots, videos, logs, or other relevant information.

---

# 6. BUG SEVERITY

### Low

Minor visual problems, spelling mistakes, or small inconveniences.

### Medium

A feature is partially broken but the server remains usable.

### High

A major feature is broken, users are significantly affected, or there is a serious gameplay/community impact.

### Critical

The issue creates a major security problem, widespread outage, significant data risk, or serious server instability.

Critical issues should be reported to Developers and Admins immediately.

---

# 7. REGRESSION TESTING

After a Developer fixes a bug, QA should verify:

* The original bug is fixed.
* The fix does not create another problem.
* Related functionality still works.
* Permissions remain correct.
* Existing features continue working.

A bug should not be marked as fixed simply because the original symptom disappeared.

---

# 8. PERMISSION TESTING

QA should test different permission levels when appropriate.

Examples:

* Regular member.
* Moderator.
* Administrator.
* Developer.
* Executive.

Verify that users can access only the features intended for their role.

---

# 9. SECURITY TESTING

QA may test whether systems properly reject unauthorized actions.

However, QA staff must not:

* Steal information.
* Access private accounts.
* Distribute vulnerabilities.
* Intentionally damage systems.
* Use vulnerabilities for personal benefit.
* Publicly release exploit instructions.

Security findings should be reported privately.

---

# 10. FEATURE TESTING

Before a feature is released, QA should verify:

* The feature works as intended.
* Commands work correctly.
* Permissions work correctly.
* Error handling works.
* Unexpected inputs are handled safely.
* The feature does not break related systems.

---

# 11. TEST RESULTS

QA should clearly communicate results.

Example:

**Status:** Passed
**Feature:** Report System
**Tested:** August 12, 2026
**Result:** Reports successfully create tickets and notify staff.
**Issues:** None found.

Or:

**Status:** Failed
**Feature:** Moderation Command
**Issue:** Members without moderation permissions can execute the command.
**Severity:** Critical
**Evidence:** Attached to QA report.

---

# 12. WORKING WITH DEVELOPERS

QA should provide Developers with useful information rather than simply saying that something is broken.

Developers should be able to understand:

* What happened.
* Where it happened.
* How to reproduce it.
* How serious it is.
* What evidence exists.

QA should also answer reasonable follow-up questions about testing.

---

# 13. WORKING WITH ADMINS

QA should notify Admins when an issue affects:

* Moderation.
* Permissions.
* Member safety.
* Server availability.
* Exploits.
* Security.
* Major public features.

QA does not decide punishments for members.

---

# 14. QA CONDUCT

QA staff must not:

* Abuse testing permissions.
* Test dangerous changes on production without authorization.
* Hide bugs.
* Falsify test results.
* Claim something passed without testing it.
* Leak unreleased features.
* Use QA access for personal benefit.

---

# 15. FINAL STANDARD

A good QA member finds problems before they become community problems.

QA should be thorough, honest, reproducible, and careful with access to internal systems.
