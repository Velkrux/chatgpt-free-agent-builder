# Quickstart — ordinary chat first

## Six manual steps

1. Open an ordinary new ChatGPT chat in your own account. Paste the block from [the compact builder](AGENT_BUILDER_PROMPT.md), replacing the idea placeholder. For this example, request an AI Release Research Assistant for your work.
2. Answer the useful questions. Read the generated instructions. Request a specific correction if an important rule or length limit was missed.
3. Start a new ordinary chat. Paste your finished instructions, the [source packet](examples/ai-release-research/SOURCE_PACKET_v1.txt) and [first-run request](examples/ai-release-research/FIRST_RUN.md). You can use the [actual saved instructions](examples/ai-release-research/PROJECT_INSTRUCTIONS.md) to inspect the worked example.
4. Check dates, citations and eligibility against the supplied sources. A URL alone is not evidence that the assistant opened it.
5. Apply the [changed requirement and conflicting note](examples/ai-release-research/HARD_CASE.md). N1 is deliberately synthetic test material. Save the actual answer before editing it.
6. Keep the instructions; supply fresh inputs manually next time. This creates no background monitoring or guaranteed memory.

This pasted-text path needs no installation, code or API key. It is intended for documented ChatGPT capabilities, but the saved behavior was tested in Codex, not ChatGPT Free. Account access and quotas still apply. A new chat here is an explicit context handoff.

## Optional Project

If your account exposes Projects, create a dedicated Project and paste the finished block into Project instructions. Add only the small source packet, then start a chat inside the Project with your first-run request. Do not change global Custom Instructions or upload the whole repository.

Project capacity and daily upload allowance are separate limits. Files do not refresh themselves when a source changes. If Projects or uploads are unavailable, use pasted text and label that fallback accurately. The actual Free Project UI, uploads and fresh chat remain NOT VERIFIED. See [official Project setup](https://help.openai.com/en/articles/10169521-projects-in-chatgpt) and [our access boundary](FREE_PLAN_LIMITATIONS.md).

## Earlier examples

[Tool Advisor](examples/ai-tool-advisor/ADVISOR_INSTRUCTIONS.md) has normal, missing-source and changed-file-size cases. [Learning Plan Coach](examples/second-use-case/LEARNING_PLAN_INPUT.md) has a different output contract. Both used [full v1](AGENT_BUILDER_PROMPT_FULL_V1.md); their genuine outputs are preserved and must not be attributed to compact v2. No actual PDF processing or learner outcome was tested.

Keep evaluator keys, private account material and the evidence archive out of the assistant's working context. Review [test discipline](TEST_CHECKLIST.md) and [validation status](VALIDATION_STATUS.md) before making a claim.
