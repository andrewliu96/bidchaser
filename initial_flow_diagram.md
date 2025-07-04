flowchart TD
    %% ─────────────────────
    %% SEARCH  ▸ Stage 1
    %% ─────────────────────
    subgraph SEARCH["Search"]
        direction TB
        S1([Jr RPL 60-100])
        S1 --> S2["Bridging<br/>• Prov<br/>• National"]
        S2 --> S3["here"]
        S1 --> S4([Smaller internet websites])
        NOTE1{{"short window<br/>(1 week) to make,<br/>no pitch"}}
    end
    S1 --> C1((10))

    %% ─────────────────────
    %% DECIDE  ▸ Stage 2
    %% ─────────────────────
    subgraph DECIDE["Decide"]
        direction TB
        C1 --> D1[SCOTSMAN]
        D1 --> D2([Debate<br/>with senior ppl])
        D2 --> D3["Summary pros/cons<br/>Case-studies<br/>Staff, do bid"]
        D3 --> D4((Publications w/ competitors,<br/>many years, LinkedIn))
        D3 --> D5((Who requested documents,<br/>how you stack))
    end

    %% ─────────────────────
    %% BID WRITING  ▸ Stage 3
    %% ─────────────────────
    subgraph BID["Bid Writing"]
        direction TB
        D3 --> B1["Bid Writing"]
        B1 --> B2((what’s soln?<br/>Unique selling))
        B2 --> B3["Filling it out, etc."]
    end

    %% ─────────────────────
    %% OPTIONAL NOTES
    %% ─────────────────────
    NOTE1:::dashed
    N1[Academic]
    N2[Consultancy]

    classDef dashed fill:#fff,stroke-dasharray: 5 5,stroke:#999;
