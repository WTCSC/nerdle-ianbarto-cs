# Nerdle Decision Tree

```
Start
  └─> Prompt: Enter guess
         ├─> Invalid input (bad format)
         │     └─> Show "Invalid guess" message
         │            └─> Back to Prompt
         ├─> Valid equation (format OK)
         │     ├─> If equation semantics invalid (e.g., parse error, division by zero)
         │     │     └─> Show "Invalid equation (bad math)" message -> Back to Prompt
         │     └─> Check against target
         │            ├─> Exact match -> Win (show success) -> End
         │            └─> Not match -> Show per-symbol feedback -> Decrement attempts
         │                      └─> If attempts left -> Back to Prompt
         │                      └─> Else -> Lose (reveal target) -> End

```

