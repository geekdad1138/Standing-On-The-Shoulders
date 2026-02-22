# Visual Dependency Graph

[← Back to Main README](../README.md)

---

```mermaid
graph TD
    %% Nodes
    Babbage[1837: Charles Babbage]
    Ada[1843: Ada Lovelace]
    Turing[1936: Alan Turing]
    Shannon[1948: Claude Shannon]
    Boole[1847: George Boole]
    Transistor[1947: Transistor Team]
    Intel[1971: Intel 4004 Team]
    Dartmouth[1956: Dartmouth Founders]
    Rosenblatt[1958: Frank Rosenblatt]
    Minsky[1969: Minsky & Papert]
    Backprop[1986: The Backprop Team]

    %% Connections
    Babbage --> Ada
    Ada --> Turing
    Turing --> Shannon
    Boole --> Shannon
    Shannon --> Transistor
    Transistor --> Intel
    Turing --> Dartmouth
    Shannon --> Dartmouth
    
    %% Era 6: Neural Networks
    Dartmouth --> Rosenblatt[1958: Frank Rosenblatt<br/>The Perceptron]
    Rosenblatt --> Minsky[1969: Minsky & Papert<br/>The XOR Challenge]
    
    %% Era 7: The Modern Revival
    Minsky --> Backprop[1986: The Backprop Team<br/>Hidden Layers / Deep Learning]
    
    %% Styling
    classDef highlight fill:#f96,stroke:#333,stroke-width:2px;
    class Backprop highlight;