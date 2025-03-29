Stoic philosophy is to heal misconceptions about what truly matters. This healing allows us to stop chasing external goods that don't bring lasting happiness and instead focus on internal growth that cannot be taken away. External circumstances (wealth, health, reputation) are largely beyond our control and inherently unstable. Basing happiness on these factors makes it fragile and temporary.

Character, is something we can develop regardless of circumstances. When you develop wisdom, courage, justice, and moderation, you carry the source of your well-being with you at all times, making you resilient to fortune's changes.
Stoics saw humans as naturally rational and social beings. By developing our character in accordance with these aspects of our nature through rational thinking and ethical behavior, we fulfill our purpose and function well as humans, which brings satisfaction.

Diagram below illustrates this relationship:

```mermaid
flowchart TD
    VIRTUES[Cardinal Virtues]


    WISDOM[Wisdom
    -
    The ability to discern what's truly good and beneficial and what is neutral or bad.
    Acting thoughtfully and rationally, making decisions based on reason rather than impulse or emotion.]
    
    COURAGE[Courage
    -
    Facing challenges, fears, or discomfort without retreating.
    Remaining steadfast, especially in difficult situations, and acting according to principles even when it’s hard.]
    
    JUSTICE[Justice
    -
    Treating others fairly, kindly, and ethically.
    Recognizing our interconnectedness and acting responsibly towards others and the broader community.]
    
    TEMPERANCE[Temperance
    -
    Moderation in desires, emotions, and behaviors.
    Avoiding excess and practicing self-discipline.]
    
    HAPPINESS[Happiness
    -
    State of inner tranquility and fulfillment, achieved by living virtuously and in harmony with nature.
    Tranquility - having a calm, clear mind, free from negative emotions like anxiety, anger, or envy.]

    
    %% Virtues breakdown
    VIRTUES --> WISDOM
    VIRTUES --> COURAGE
    VIRTUES --> JUSTICE
    VIRTUES --> TEMPERANCE
    
    %% Key relationships between virtues and happiness
    
    WISDOM -->|"Allows to examine our judgments and manage our responses, freeing us from destructive emotions like anger, fear, and envy that cause suffering."| HAPPINESS
    WISDOM -->|"Helps to distinguish between what we can and cannot control, accept what we cannot change and focus on what we can control"| HAPPINESS

    COURAGE -->|"Empowers us to calmly handle life's difficulties, preserving inner peace."| HAPPINESS
    
    JUSTICE -->|"Strengthens social relationships and community bonds, enhancing satisfaction and harmony."| HAPPINESS
    
    TEMPERANCE -->|"Prevents excessive desires and attachments, promoting tranquility and contentment with what we have"| HAPPINESS

```



```mermaid
flowchart TD
    DICHOTOMY["The Dichotomy of Control"]
    
    DICHOTOMY --> CONTROLLABLE["Within Our Control
    -
    Our judgments, intentions,
    desires, and actions"]
    
    DICHOTOMY --> UNCONTROLLABLE["Beyond Our Control
    -
    External circumstances,
    others' actions, reputation,
    wealth, health, etc."]
    
    CONTROLLABLE --> VIRTUES_BOX
    
    subgraph VIRTUES_BOX["Cardinal Virtues"]
        WISDOM["Wisdom
        -
        Discernment between true goods,
        indifferents, and harms
        
        Clear judgment and rational thinking"]
        
        COURAGE["Courage
        -
        Facing challenges and fears with steadfastness
        
        Acting according to principles
        despite difficulty"]
        
        JUSTICE["Justice
        -
        Ethical treatment of others
        
        Living in harmony with
        our social nature"]
        
        TEMPERANCE["Temperance
        -
        Moderation in desires and actions
        
        Self-discipline and contentment"]
    end
    
    subgraph HAPPINESS["Happiness"]
        TRANQUILITY["Tranquility
        -
        Calm, clear mind free from 
        negative emotions like anxiety,
        anger, and envy"]
        
        FULFILLMENT["Fulfillment
        -
        Deep satisfaction from living
        virtuously and in harmony
        with our nature"]
    end
    
    %% Paths to happiness through virtues
    WISDOM -->|"Provides clarity about what truly matters
    and freedom from destructive emotions"| TRANQUILITY
    
    COURAGE -->|"Enables facing life's challenges
    without disturbance"| TRANQUILITY
    
    JUSTICE -->|"Fulfills our social nature through
    right relations with others"| FULFILLMENT
    
    TEMPERANCE -->|"Prevents excessive desires that
    disturb peace of mind"| TRANQUILITY
    
    WISDOM -->|"Allows living according to
    nature and reason"| FULFILLMENT
    
    %% The relationship with uncontrollables
    UNCONTROLLABLE -->|"Accepting what we cannot change"| TRANQUILITY
    
    %% Adding style classes
    classDef primary fill:#e6f7ff,stroke:#1890ff,stroke-width:2px;
    classDef secondary fill:#fff1f0,stroke:#ff4d4f,stroke-width:1px;
    classDef virtue fill:#f6ffed,stroke:#52c41a,stroke-width:1.5px;
    classDef happiness fill:#fff0f6,stroke:#eb2f96,stroke-width:2px;
    classDef component fill:#f9f0ff,stroke:#722ed1,stroke-width:1.5px;
    
    class DICHOTOMY primary;
    class CONTROLLABLE,UNCONTROLLABLE secondary;
    class VIRTUES_BOX virtue;
    class WISDOM,COURAGE,JUSTICE,TEMPERANCE virtue;
    class HAPPINESS_BOX happiness;
    class TRANQUILITY,FULFILLMENT component;
```
