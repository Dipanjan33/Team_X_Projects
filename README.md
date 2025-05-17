# Team_X_Projects

# 🎉PROJECT OVERVIEW
[GITHUB](https://github.com/Dipanjan33/Team_X_Projects)

[Youtube](https://www.youtube.com/)
- jj
- ooo
- ooo

```mermaid
flowchart TD
    A[Start] --> B[Capture Image]
    B --> C[Convert to HSV]
    C --> D[Segment Blue and Orange Portions]
    D --> H[Apply Hough Line Transform]
    H --> E{Blue Before Orange?}
    E -->|Yes| F[Set Right-Based Orientation]
    E -->|No| G[Set Left-Based Orientation]
    F --> I[Count Detected Lines]
    G --> I
    I --> J{Lines Counted >= 12?}
    J -->|No| K[Calculate Error]
    K --> L[PID Controller Adjusts Steering]
    L --> M[Continue Navigation]
    M --> B
    J -->|Yes| N[Delay and Stop]
    N --> O[End]


flowchart TD 
    A[Start] --> B[Capture Image]
    B --> H[Amma]
```
    
