``` mermaid
flowchart TD
    A[“The Four Great Number Spells<br/>All Part of One Magical Family”] --> B
    
    subgraph B [The Spell Relationships]
        B1[“Addition Charm<br/>Putting numbers together”]
        B2[“Subtraction Charm<br/>Taking numbers apart”]
        B3[“Multiplication Charm<br/>Quick duplication”]
        B4[“Division Charm<br/>Fair sharing”]
    end

    B1 --> C1[“OPPOSITE SPELLS<br/>They undo each other's magic”]
    B2 --> C1
    
    B3 --> C2[“OPPOSITE SPELLS<br/>They reverse each other's effects”]
    B4 --> C2

    B1 --> D1[“Multiplication is really<br/>SECRET ADDITION repeated many times”]
    B3 --> D1
    
    B2 --> D2[“Division is really<br/>SECRET SUBTRACTION repeated until zero”]
    B4 --> D2

    C1 --> E[“Example: 5 + 3 = 8 then 8 - 3 = 5<br/>You're back where you started!”]
    C2 --> F[“Example: 4 × 3 = 12 then 12 ÷ 3 = 4<br/>The magic is reversed!”]
    D1 --> G[“Example: 4 × 3 = 4 + 4 + 4 = 12<br/>Adding four three times!”]
    D2 --> H[“Example: 12 ÷ 3 = count subtractions of 3<br/>12-3=9, 9-3=6, 6-3=3, 3-3=0 → 4 times!”]
```
