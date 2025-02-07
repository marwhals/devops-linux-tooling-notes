```mermaid
graph TD
    A[Start] --> B{Is it working?}
    B -->|Yes| C[Good job!]
    B -->|No| D[Fix the issue]
    D --> B
