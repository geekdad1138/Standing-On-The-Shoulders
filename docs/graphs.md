# Visual Dependency Graph

This graph visualizes how each "shoulder" connects to the next.

```mermaid

graph TD
    %% Era 1: Mechanical & Early Logic
    Babbage[1837: Charles Babbage<br/>Mechanical Engine] --> Ada[1843: Ada Lovelace<br/>Universal Computation]
    
    %% Era 2: The Proofs
    Ada --> Turing[1936: Alan Turing<br/>Universal Machine]
    
    %% Era 3: Physical Implementation
    Turing --> Shannon[1948: Claude Shannon<br/>Information Theory / Bits]
    Boole[1847: George Boole<br/>Boolean Logic] --> Shannon
    
    %% Era 4: The Hardware Leap
    Shannon --> Transistor[1947: Transistor Team<br/>Solid-State Logic]
    Transistor --> Intel[1971: Intel 4004 Team<br/>Microprocessor]
    
    %% Era 5: The AI Birth & Struggle
    Turing --> Dartmouth[1956: Dartmouth Founders<br/>Artificial Intelligence]
    Shannon --> Dartmouth
    
    %% Era 6: Neural Networks
    Dartmouth --> Rosenblatt[1958: Frank Rosenblatt<br/>The Perceptron]
    Rosenblatt --> Minsky[1969: Minsky & Papert<br/>The XOR Challenge]
    
    %% Era 7: The Modern Revival
    Minsky --> Backprop[1986: The Backprop Team<br/>Hidden Layers / Deep Learning]
    
    %% Styling
    classDef highlight fill:#f96,stroke:#333,stroke-width:2px;
    class Backprop highlight;