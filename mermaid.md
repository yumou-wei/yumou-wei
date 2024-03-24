flowchart LR
    A[Get url] -->|Extract article content| B
    B -->|Match <div> elements| C
    C -->|Join matches| D
    D -->|Remove characters that are not words/whitespaces| E
    E -->|Cleaned article content| F
