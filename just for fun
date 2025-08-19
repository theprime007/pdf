```mermaid
graph TD
    A[User Interface] --> B{Frontend Application}
    B --> C[Test Management Module]
    B --> D[Performance Analytics Module]
    B --> E[Export Module]
    C --> F[State Management]
    C --> G[Question Handler]
    D --> H[Data Aggregator]
    D --> I[Visualization Engine]
    E --> J[Google Sheets Integration]
    E --> K[Excel Export]

    subgraph Test Management Module
        F[State Management]
        G[Question Handler]
        F --> L[LocalStorage for temporary test data]
        F --> M[IndexedDB for offline data storage]
        G --> N[Dynamic Question Rendering]
        G --> O[Question Navigation]
        G --> P[Bookmarking System]
    end

    subgraph Performance Analytics Module
        H[Data Aggregator]
        I[Visualization Engine]
        H --> Q[Subject-wise Aggregation]
        H --> R[Trend Analysis]
        I --> S[Charts for Accuracy Trends]
        I --> T[Topic-wise Breakdown Visualization]
        I --> U[Summary of Performance Metrics]
    end

    subgraph Export Module
        J[Google Sheets Integration]
        K[Excel Export]
        J --> V[Google OAuth2 Authentication]
        J --> W[Google Sheets API Push Data]
        K --> X[SheetJS for Excel File Generation]
        K --> Y[Download .xlsx File]
    end

    subgraph User Actions
        A --> Z[Take Test]
        A --> AA[View Results]
        A --> AB[Export Data]
        AB --> AC[Export to Google Sheets]
        AB --> AD[Export to Excel]
    end

    subgraph Google Sheets Integration
        V --> AE[User Authentication Popup]
        W --> AF[Create New Sheet or Append Data]
        W --> AG[Organize Data by Subjects]
    end

    subgraph Excel Export
        X --> AH[Generate Excel File Locally]
        Y --> AI[Provide Download Button]
    end

    style A fill:#f9f,stroke:#333,stroke-width:2px
    style B fill:#bbf,stroke:#333,stroke-width:2px
    style C fill:#bbf,stroke:#333,stroke-width:2px
    style D fill:#bbf,stroke:#333,stroke-width:2px
    style E fill:#bbf,stroke:#333,stroke-width:2px
    style Z fill:#cfc,stroke:#333,stroke-width:2px
    style AA fill:#cfc,stroke:#333,stroke-width:2px
    style AB fill:#cfc,stroke:#333,stroke-width:2px
    style AC fill:#cfc,stroke:#333,stroke-width:2px
    style AD fill:#cfc,stroke:#333,stroke-width:2px
```
