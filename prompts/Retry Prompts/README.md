# Retry Prompts

This directory contains the 3 different retry prompt templates used when the previous suggestion did not successfully repair the model.

- `error_retry_prompt.md`: Used when the previous suggestion resulted in a model that created syntax errors, type errors, or
violations of variables’ occurrence rules in the Rodin Platform.
- `failing_proof_retry_prompt.md`: Used when the previous suggestion resulted in a model without errors, syntax errors, type errors, or
violations of variables’ occurrence rules, but the Rodin Platform still reports undischarged proof obligations.
- `unsupported_operation_retry_prompt.md`: Used when the previous suggestion contains operations that are not supported by the Rodin Platform, or are in an incorrect format.