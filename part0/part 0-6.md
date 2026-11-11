```mermaid
sequenceDiagram
    participant Browser
    participant Server
    Browser->>+Server: POST https://fullstackexampleapp.herokuapp.com/new_notes_spa
    Server-->>-Browser: 201 created
```
