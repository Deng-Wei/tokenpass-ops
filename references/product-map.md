# TokenPass Product Map

This is a public-safe summary of the product concepts in the TokenPass materials reviewed in November 2026. It is a map of intended product scope, not proof that every item is implemented or currently available. Check the active code and production behavior before describing any capability as live.

## Product purpose

TokenPass is intended to help people compare AI model API prices and make cost-aware choices. The broader product direction connects three decisions:

1. Which model capability level fits a task?
2. Which compatible provider or route is suitable and less expensive?
3. How can users track changes and understand the evidence behind a recommendation?

## Product areas in the source plans

| Area | Intended user value | Status caution |
|---|---|---|
| Model and provider price comparison | Compare model prices and provider routes | Verify current coverage, freshness, and source data in the live catalog. |
| Price change alerts | Notify users about changes to models they follow | Verify subscription flow, delivery, and current preferences. |
| Personal routing | Choose among user-authorized routes while keeping credentials and requests local | Product plan only; verify implementation and privacy architecture before claiming availability. |
| Task-to-model fit | Suggest a lower-cost model when the task appears to need less capability | Roadmap concept; treat as planned unless current code and user-facing behavior prove otherwise. |
| Team controls and cost views | Apply shared policies, budgets, usage views, and exports | Team product concept; confirm which parts have shipped before presenting them as available. |
| Local or private deployment | Support organizations that need tighter control over requests and credentials | Enterprise direction; do not imply a deployment option exists without current release evidence. |

## Product principles to preserve

- Cost savings must not come at the expense of unsuitable output quality. Be conservative when task or model fit is unclear.
- Explain why a route or model is recommended and what evidence supports the price comparison.
- Keep product copy aligned with actual behavior. Distinguish intended privacy architecture from verified implementation.
- Do not repeat old pricing, market-size, ROI, conversion, or revenue assumptions as current facts. Recalculate from current evidence when needed.
- Preserve the separation between personal workflows and team administration; do not imply a personal feature automatically covers team governance.

## Public communication

When writing public copy, make claims only after checking current implementation and production behavior. Prefer dated, measurable statements with a source over unqualified phrases such as “real-time,” “automatic,” “guaranteed savings,” or “private by design.”
