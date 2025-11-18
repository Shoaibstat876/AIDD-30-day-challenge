
✅ PART B — PRACTICAL TASK (FINAL VERSION FOR SUBMISSION)
1⃣ CLI Prompt (exact text you used)
gemini "Generate a 1-paragraph specification for an email validation function. It must contain '@', include a valid domain like .com or .org, and return clear error messages for invalid input."

2⃣ CLI Output (Generated Specification)

Specification:

The email validation function will accept a string as input and return a boolean indicating validity, along with a descriptive error message if invalid. A valid email address must contain exactly one '@' symbol, with at least one character before it and at least one character after it. The domain part (after the '@') must include a top-level domain (TLD) such as '.com', '.org', '.net', '.edu', or '.gov', preceded by at least one character. The function will provide specific error messages for cases like missing '@', multiple '@' symbols, invalid domain format, or unsupported TLDs.