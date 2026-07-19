# Case Study 04 – Detecting AI Hallucinations

## Domain

AI Safety and Response Evaluation

---

# Objective

Evaluate an AI-generated response to identify factual inaccuracies, unsupported claims, and signs of hallucination.

---

# User Prompt

Who invented the first commercially successful smartphone?

---

# AI Response

Apple invented the first commercially successful smartphone in 2007 with the original iPhone. Before the iPhone, no commercially successful smartphones existed.

---

# Evaluation

| Criterion | Score | Comments |
|-----------|:----:|----------|
| Accuracy | 2/5 | The iPhone was highly successful, but earlier smartphones such as BlackBerry and IBM Simon existed. |
| Completeness | 2/5 | Ignores important historical context. |
| Clarity | 5/5 | Easy to understand. |
| Logical Reasoning | 3/5 | Makes an unsupported absolute claim. |
| Evidence | 2/5 | No supporting references or historical comparison. |
| Instruction Following | 5/5 | Answers the prompt, but incompletely. |
| Writing Quality | 5/5 | Well written. |

---

# Overall Score

**24 / 35 (69%)**

---

# Hallucination Indicators

- Uses the word **"first"** incorrectly.
- Ignores earlier smartphone devices.
- Makes an absolute claim without evidence.
- Omits important historical milestones.

---

# Improved Response

Apple did not invent the first smartphone. Earlier devices such as the IBM Simon (1994) and BlackBerry smartphones were already available. However, the original iPhone, introduced in 2007, is widely recognized for transforming the smartphone industry by combining a multi-touch interface, full web browsing, and a strong application ecosystem, making it one of the first massively successful modern smartphones.

---

# Lessons Learned

- Confident wording does not guarantee correctness.
- Historical claims should be verified.
- Absolute statements require supporting evidence.
- AI evaluators should distinguish between innovation and invention.

---

# Final Recommendation

**Needs Improvement**

The response is readable but contains a significant historical inaccuracy that should be corrected before being presented to users.