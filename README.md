# Decision Systems Methods

Complex technical decisions are rarely difficult because information is completely absent.

They are difficult because the information is incomplete, the requirements interact, assumptions are easy to overlook, and different interpretations can lead to very different conclusions.

My interest in decision systems comes from working in situations where the answer is not obvious and where getting to a defensible conclusion requires more than simply finding a reference or running a calculation.

The purpose of this repository is to document some general principles I use when thinking through those situations.

It is not intended to replace professional judgment. The goal is to make the reasoning around that judgment easier to understand, question, and revise when better information becomes available.

## Start With the Actual Decision

Before getting deep into analysis, I try to understand what decision is really being made.

The same technical condition can mean very different things depending on the objective.

A question about a building, system, project, or technical issue may look the same at first, but the analysis changes depending on whether someone is trying to design it, acquire it, approve it, repair it, challenge it, estimate it, or decide whether to proceed at all.

That is why I prefer to start with a few basic questions.

What are we trying to accomplish? What decision needs to be supported? What constraints already exist? What would a successful outcome look like? What are the consequences if the conclusion is wrong?

Those questions usually matter more than jumping directly into the technical details.

## Evidence Is Not the Same as a Conclusion

A credible source does not automatically produce a credible conclusion.

The more important question is whether the source actually applies to the situation being evaluated.

A report, standard, code provision, test result, prior decision, or technical reference may be perfectly valid and still be the wrong basis for the current case.

Conditions may be different. The jurisdiction may be different. The project type, material, system configuration, time period, or underlying assumptions may not match.

So the question is not simply whether evidence exists.

The question is whether that evidence legitimately supports the conclusion being made.

## Keep Assumptions Visible

Assumptions are often necessary in technical work.

The problem starts when they stop looking like assumptions and quietly become treated as facts.

When an important conclusion depends on an assumption, I want to know why that assumption was used, what supports it, how sensitive the conclusion is to it, and what happens if it turns out to be wrong.

Some assumptions barely matter.

Others can completely change the result.

Those should not be treated the same way.

## Unknown Does Not Mean False

One of the easiest mistakes in technical decision-making is to turn missing information into a negative answer.

If something has not been established, that does not necessarily mean it is false.

It may simply be unresolved.

The distinction matters because uncertainty should remain visible until there is enough evidence to support a stronger conclusion.

Artificial certainty is often more dangerous than an honest unknown.

## Conflict Should Be Understood Before It Is Resolved

Technical information does not always agree.

Two professionals may interpret the same requirement differently. Two methods may produce different results. Two credible sources may appear to conflict.

When that happens, I try to understand the source of the disagreement before deciding which position is stronger.

Are the sources actually addressing the same condition? Are they using the same definitions? Are their assumptions different? Is one being applied outside its intended scope?

Sometimes the disagreement disappears once the underlying conditions are compared carefully.

Sometimes it does not.

Either way, the disagreement itself is useful information.

## Test the Conclusion Before Accepting It

A conclusion becomes more credible when it survives an attempt to disprove it.

Before accepting an important result, I try to ask what could make it wrong.

What evidence would contradict it? Which assumption matters most? Could another interpretation change the outcome? Is an important interface being missed? Has precedent been reused without confirming that the original conditions still apply?

A strong review should not only collect support for the preferred answer.

It should also look for credible reasons that answer may fail.

## Consider Alternatives Before Locking In

Technical teams can become attached to the first solution that appears reasonable.

That is why I think it is useful to consider alternatives before a preferred answer becomes entrenched.

The alternative does not always need to be another design.

It may be a different interpretation, a different assumption, a different sequence of work, a mitigation measure, or even delaying a decision until one important unknown is resolved.

The goal is not to create unnecessary options.

It is to make sure the preferred path remains the strongest one after reasonable alternatives have been considered.

## Decisions Can Change

A good technical decision should be defensible based on the information available at the time.

That does not mean it should become permanent.

If material information changes, the conclusion may need to change with it.

When that happens, the important questions are straightforward: what changed, why does it matter, which earlier conclusions depended on it, and does the original decision still hold?

Changing a conclusion because the evidence changed is not a weakness.

It is part of good technical judgment.

## Professional Judgment Still Matters

Structured reasoning does not eliminate professional judgment.

In many cases it makes that judgment more important because it becomes clearer where judgment was actually used.

The objective is not to create automated certainty.

It is to make difficult technical decisions more transparent, more defensible, and easier to revisit when conditions change.

## Case Studies

[Technical Due Diligence With Incomplete Information](examples/01-technical-due-diligence-case-study.md)

A fictional example showing how I would approach an acquisition decision when the available technical information is incomplete and some of the remaining uncertainty could materially affect cost, schedule, or feasibility.

## About This Repository

The material here is intentionally general and non-confidential.

The examples are intended to demonstrate approaches to technical reasoning, evidence, uncertainty, assumptions, alternatives, and decision review.

They do not reproduce proprietary systems, confidential project information, employer-specific procedures, or protected implementation methods.

Created by [Ehsan Mohajerani, P.E.](https://github.com/ehsanmohajerani)

[LinkedIn](https://www.linkedin.com/in/ehsanmohajerani)
