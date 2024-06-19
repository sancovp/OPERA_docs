graph TD
    A[Start: Evolutionary Intent] --> B[Construct Chain]
    B --> C[Procreate New Agent]
    C --> D[Awaken New Progeny]
    D --> E[Progeny Forges Capabilities]
    E --> F[Test Capabilities]
    F --> G{Capabilities Active?}
    G -->|Yes| H[Progeny Available for Work]
    G -->|No| I[Notifications for HITL]
    I --> J[HITL Solves Problems]
    J --> K[Make Operational]
    K --> L[System Evolves]
    L --> A

    subgraph OPERA
        A1[Ontomata] --> A2[Progenitor]
        A2 --> A3[Evolutionary]
        A3 --> A4[Reliquary]
        A4 --> A5[Agent]
    end

    subgraph autoProgenitor
        B1[Construct Chain] --> B2[Procreate New Agent]
        B2 --> B3[Awaken New Progeny]
        B3 --> B4[Progeny Forges Capabilities]
        B4 --> B5[Test Capabilities]
        B5 --> B6{Capabilities Active?}
        B6 -->|Yes| B7[Progeny Available for Work]
        B6 -->|No| B8[Notifications for HITL]
        B8 --> B9[HITL Solves Problems]
        B9 --> B10[Make Operational]
        B10 --> B11[System Evolves]
        B11 --> B1
    end

    A --> OPERA
    B --> autoProgenitor
    C --> autoProgenitor
    D --> autoProgenitor
    E --> autoProgenitor
    F --> autoProgenitor
    G --> autoProgenitor
    H --> autoProgenitor
    I --> autoProgenitor
    J --> autoProgenitor
    K --> autoProgenitor
    L --> autoProgenitor
