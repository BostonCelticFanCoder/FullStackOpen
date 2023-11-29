squenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa 
    activate server
    server-->>browser: {content: "abra", date: "2023-11-29T01:18:38.394Z"}
    deactivate server

