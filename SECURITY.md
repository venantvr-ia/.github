# Security Policy

## Scope

This policy covers all repositories under the **venantvr-ia** organization. These projects involve artificial intelligence, machine learning, natural language processing, and data pipelines.

## Reporting a Vulnerability

If you discover a security vulnerability in any of these repositories, please report it responsibly:

1. **Do not open a public issue.** Security vulnerabilities must be reported privately.
2. Go to the affected repository's **Security** tab and click **"Report a vulnerability"** to create a private security advisory.
3. Include as much detail as possible: affected files, steps to reproduce, and potential impact.

## What We Consider Security Issues

- API key or token exposure (OpenAI, Google, HuggingFace, etc.)
- Prompt injection vulnerabilities in LLM-based tools
- Training data leakage or exfiltration paths
- Insecure deserialization of model files (pickle, joblib)
- Server-side request forgery through model inference endpoints
- Hardcoded credentials or secrets

## Response

- Acknowledgment within **72 hours**
- Status update within **7 days**
- If confirmed, a fix will be prioritized and you will be credited (unless you prefer anonymity)

## Out of Scope

- Archived repositories (kept for reference, not actively maintained)
- Jupyter notebooks used for experimentation — unless they contain leaked credentials
- Model accuracy or bias issues (these are quality concerns, not security vulnerabilities)
