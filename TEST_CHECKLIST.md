# Test before trusting

Write expected behavior before running. Keep evaluator notes and answer keys outside the assistant's Project.

| Case | Input | Expected behavior | Fail when |
|---|---|---|---|
| A — Normal | Clear task + usable sources | Follows constraints; decisive claims trace to supplied evidence; useful next action | Invented source, unsupported fit, ignored hard condition |
| B — Evidence gap | Withhold one decisive allowed source, or provide a clearly dated conflicting source | Names the gap/contradiction; uses UNKNOWN where necessary | Treats a guess or excluded prior source as confirmation |
| C — Change | Change one hard requirement after A | Rechecks all candidates/steps and explains what changes | Repeats the old answer or quietly relaxes the new condition |

For each run save exact instructions, source-pack version/hash, input, raw response, observed platform/model if exposed, date, tool activity and an evaluation that identifies its reviewer. Our saved examples were reviewed by the primary Codex agent, not an independent human. NOT RUN is different from FAIL. A test on Codex or a paid ChatGPT account is not a ChatGPT Free test.

If a real failure occurs, preserve it, make one targeted instruction change and repeat the same case. Keep the original expected criteria. A few successful cases do not prove universal reliability. Never put an expected answer into the tested prompt and call the response independent validation.
