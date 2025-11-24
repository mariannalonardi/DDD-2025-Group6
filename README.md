## DDD-2025-Group6
Elisa Caridi, Marianna Lonardi, Giorgia Salmoiraghi

# The Evolution of Human Interstellar Communication Strategies

## Visualisation
<img width="1919" height="869" alt="image" src="https://github.com/user-attachments/assets/4129db15-d92b-4f41-95ea-3a8a3c9ec4d0" />

[Visualisation](https://mariannalonardi.github.io/DDD-2025-Group6/)

## Abstract 
This project analyzes the progression of human interstellar messages over time, considering transmission techniques, target selection, and design strategies. The study specifically focuses on encoding types and purposes across different periods, distances in light-years, and projected arrival times of the messages. It examines the predominant communication modes and investigates whether transmission frequency is influenced by the complexity or digital nature of the message. Insights emerge from structured data and visualizations, identifying key messages that shaped communication approaches and revealing trends in technological evolution and strategic choices in interstellar messaging.

## Protocol diagram
<img width="5253" height="2414" alt="Untitled diagram-2025-11-23-181245" src="https://github.com/user-attachments/assets/f7010503-26f6-4db4-b485-a6266488c9ac" />
'''mermaid
config:
  layout: fixed
---
flowchart LR
    Topic["<b>Topic</b>:<br>UFO communication"] --> RQ_Main["<b>Research question</b>:<br>How have human-sent interstellar messages evolved over time in their transmission parameters, destinations, and design strategies,<br>and which messages are most significant from a communication-strategy perspective?"]
    RQ_Main --> Action_Main{"<b>Action</b>:<br>Analyzed and merged multiple datasets about human–UFO communication"} & Action_Failed{"<b>Discarded action</b>:<br>Focusing on the country where messages originate was not relevant"}
    Action_Main --> Tool1(("<b>Tool 1</b>:<br>Data preprocessing / filtering with Excel"))
    Tool1 --> Dataset[("<b>Dataset</b><br>Interstellar Messages")]
    Dataset --> AllCols["<b>All data columns</b><br>
      Year<br>
      Project<br>
      Type<br>
      Institution<br>
      Frequency<br>
      Transmitter power<br>
      Destination name<br>
      Destination type<br>
      Year of arrival<br>
      Distance in light years<br>
      Code type<br>
      Country<br>
      Scope"]
    AllCols --> SelectedCols["<b>Data columns (selected)</b><br>
    Year<br>
    Project<br>
    Type<br>
    Frequency<br>
    Destination name<br>
    Destination type<br>
    Year of arrival<br>
    Distance in light years<br>
    Code type"]
    SelectedCols --> Tool2(("<b>Tool 2</b>:<br>Visual Studio Code and Flourish"))
    Tool2 --> Action_Tool2{"<b>Action</b>:<br>Processed and structured data for visualization"}
    Action_Tool2 --> DataViz["<b>Data visualization</b>:<br>Evolution of Interstellar Messages Over Time (1960–2023)"]
    DataViz --> Insights["<b>Insight / Findings</b>:<br>From technical experimentation to cultural messaging

More complexity, not just more power

More ambitious and targeted goals"]
    Topic -.-> RQ_Optional1["<b>Considered question</b>:<br>Is there a correlation between UFO shape and weather conditions (fog, clouds, light pollution)?"] & RQ_Optional2["<b>Considered question</b>:<br>Are there countries with strong UFO belief but few reported sightings,<br>and what cultural or environmental factors explain this?"]
    RQ_Optional1 -.-> Action_Optional1{"<b>Action</b>:<br>Analyzed dataset on UFO shapes and weather patterns"}
    RQ_Optional2 -.-> Action_Optional2{"<b>Action</b>:<br>Compared belief levels with sighting reports across countries"}

    RQ_Main@{ shape: rounded}
    RQ_Optional1@{ shape: rounded}
    RQ_Optional2@{ shape: rounded}
     Topic:::Pine
     RQ_Main:::Aqua
     Action_Main:::Ash
     Action_Failed:::failed
     Tool1:::Peach
     Dataset:::Rose
     AllCols:::Sky
     SelectedCols:::Sky
     Tool2:::circle
     Tool2:::Peach
     Action_Tool2:::Ash
     DataViz:::subroutine
     Insights:::hexagon
     RQ_Optional1:::Aqua
     RQ_Optional2:::Aqua
     Action_Optional1:::Ash
     Action_Optional2:::Ash
    classDef dashed stroke-dasharray: 5 5, stroke:#555
    classDef failed fill:#d3d3d3, stroke:#888, color:#000
    classDef Pine stroke-width:1px, stroke-dasharray:none, stroke:#254336, fill:#27654A, color:#FFFFFF
    classDef Aqua stroke-width:1px, stroke-dasharray:none, stroke:#46EDC8, fill:#DEFFF8, color:#378E7A
    classDef Ash stroke-width:1px, stroke-dasharray:none, stroke:#999999, fill:#EEEEEE, color:#000000
    classDef Peach stroke-width:1px, stroke-dasharray:none, stroke:#FBB35A, fill:#FFEFDB, color:#8F632D
    classDef Rose stroke-width:1px, stroke-dasharray:none, stroke:#FF5978, fill:#FFDFE5, color:#8E2236
    classDef circle stroke-width:1px, stroke-dasharray:none, stroke:#5555FF, fill:#DDEEFF, color:#000
    classDef subroutine stroke-width:1px, stroke-dasharray:none, stroke:#FFAA00, fill:#FFF3DD, color:#000
    classDef hexagon stroke-width:1px, stroke-dasharray:none, stroke:#AA00FF, fill:#F3DDFF, color:#000
    classDef Sky stroke-width:1px, stroke-dasharray:none, stroke:#374D7C, fill:#E2EBFF, color:#374D7C

    '''mermaid


## What topic does the project address? 
The project addresses the topic of human interstellar communication, specifically investigating how messages sent by humans to potential extraterrestrial recipients have evolved over time. From our research question, that is "How have human‑sent interstellar messages evolved over time in terms of their transmission parameters, destinations, and design strategies, and which of these messages can be considered the most significant from a communication‑strategy perspective?", we examine changes in transmission techniques, target selection, encoding types, message purposes, distances and how technological and strategic considerations have influenced the design and delivery of these messages.

## What data have you considered? 
The project considers a mix of publicly accessible sources documenting human-sent interstellar messages, including:
- Historical and journalistic accounts describing attempts to communicate with extraterrestrial intelligence, such as the Amusing Planet article listing notable human interstellar transmissions.
- Partial dataset, encyclopedic and technical references, such as the Wikipedia list of interstellar radio messages and the Voyager Golden Record entry, detailing message content, design strategies, and delivery methods.

These sources together provide a comprehensive dataset for analyzing the evolution of message design and communication strategies in human interstellar messaging.

Main link:
- https://www.amusingplanet.com/2024/06/the-dozen-times-humans-have-tried-to.html
- https://en.wikipedia.org/wiki/List_of_interstellar_radio_messages?utm_source
- https://it.wikipedia.org/wiki/Voyager_Golden_Record?utm_source

<img width="1914" height="229" alt="image" src="https://github.com/user-attachments/assets/256e53e6-af27-4a40-a886-fdce34136d62" />


### Link to the dataset
https://docs.google.com/spreadsheets/d/1PBxZmiyp0CESrsS1gliosT1f5524Eus-cz922S-G3gc/edit?gid=0#gid=0

## What does the visualisation show?
