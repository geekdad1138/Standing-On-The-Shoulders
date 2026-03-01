# Visual Dependency Graph

[← Back to Main README](../README.md)

---

```mermaid
graph TD
    %% Lineage A: The Logical Foundations
    Boole[1847: George Boole]
    Babbage[1837: Charles Babbage]
    Ada[1843: Ada Lovelace]
    Turing[1936: Alan Turing]
    
    %% Lineage B: The Physical Foundations (Hardware)
    Shannon[1948: Claude Shannon]
    Transistor[1947: Transistor Team]
    Intel[1971: Intel 4004 Team]
    
    %% Lineage C: The Connectionist Path (AI Theory)
    Dartmouth[1956: Dartmouth Founders]
    Rosenblatt[1958: Frank Rosenblatt]
    Minsky[1969: Minsky & Papert]
    Backprop[1986: The Backprop Team]
    LSTM[1997: Hochreiter & Schmidhuber]
    AlexNet[2012: The ImageNet Moment]
    
    %% Lineage D: The Visual/Biological Path
    Hubel[1962: Hubel & Wiesel]
    Fukushima[1980: Kunihiko Fukushima]
    LeCun[1989: Yann LeCun]

    %% Connections
    Babbage --> Ada
    Ada --> Turing
    Turing --> Shannon
    Boole --> Shannon
    Shannon --> Transistor
    Transistor --> Intel
    Turing --> Dartmouth
    Shannon --> Dartmouth
    Dartmouth --> Rosenblatt
    Rosenblatt --> Minsky
    Minsky --> Backprop
    Backprop --> LSTM
    Backprop --> AlexNet
    Intel --> AlexNet
    
    %% The Visual Logic Flow
    Hubel --> Fukushima
    Fukushima --> LeCun
    Backprop --> LeCun
    LeCun --> AlexNet

    %% Clickable Links (Cleaned Syntax for GitHub)
    click Boole "[https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1847-George-Boole.md](https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1847-George-Boole.md)" _top
