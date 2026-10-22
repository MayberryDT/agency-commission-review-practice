# Instructions inside a source message

Practice distinguishing a sender's request from an instruction aimed at the AI reading it. All messages and references below are fictional and AI-assisted teaching material. No customer records or actual model outputs are included.

Use a test setup with no access to real mail, agency records or tools that send, update or delete. This exercise supplies plain text; it does not configure or verify any tool's permissions.

1. Read [the task instructions](task-instructions.md).
2. Give your chosen test tool those instructions and [the fictional messages](fictional-messages.md). Do not provide the authored key. You may also work through the messages yourself.
3. Preserve the output separately and record what you actually observe in [the blank review sheet](review-blank.csv). If you do not run a tool, leave tool-result fields blank.
4. Then open [the separate authored review](AUTHORED-REVIEW.md). Compare source references, review claims and treatment of the embedded instruction. Record both mistakes and useful handling.

The third message is an ordinary request about wording. It helps check whether a reviewer is treating every instruction-like sentence as hostile. Quoting a sender's request is different from granting that sender control of the assistant.

The general technical concept is indirect prompt injection: instructions within external material can redirect an AI system. See [OWASP's LLM Prompt Injection Prevention Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/LLM_Prompt_Injection_Prevention_Cheat_Sheet.html) for the broader topic. These fictional inputs and review notes are original; no OWASP sample prompt, code or benchmark is reproduced.

Three simple messages cannot establish security, attack coverage, model accuracy or production suitability. A correct written answer also does not prove that connected tools enforce permissions. No live system is tested here, and no customer or vendor result is claimed. Keep source material separate from task instructions; enforce actual tool permissions outside model-generated assurances.

This extends the existing [agency practice collection](../../README.md). It does not authorize insurance decisions, account access or sending. Tyler Mayberry runs Cirlet, which offers paid AI and automation help; the fictional material was prepared with AI assistance. The repository's existing no-reuse-license statement is unchanged.
