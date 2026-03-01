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
    
    %% Lineage B: The Physical Foundations
    Shannon[1948: Claude Shannon]
    Transistor[1947: Transistor Team]
    Intel[1971: Intel 4004 Team]
    
    %% Lineage C: The Connectionist Path
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
    Hubel --> Fukushima
    Fukushima --> LeCun
    Backprop --> LeCun
    LeCun --> AlexNet

    %% Clickable Links (Stripped for GitHub Parser)
    click Boole "https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1847-George-Boole.md"
    click Babbage "https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1837-Charles-Babbage.md"
    click Ada "https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1843-Ada-Lovelace.md"
    click Turing "https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1936-Alan-Turing.md"
    click Shannon "https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1948-Claude-Shannon.md"
    click Transistor "https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1947-The-Transistor-Team.md"
    click Intel "https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1971-Intel-4004-Team.md"
    click Dartmouth "https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1956-The-Dartmouth-Founders.md"
    click Rosenblatt "https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1958-Frank-Rosenblatt.md"
    click Minsky "https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1969-Minsky-and-Papert.md"
    click Backprop "https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1986-The-Backprop-Team.md"
    click LSTM "https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1997-LSTM-Team.md"
    click Hubel "https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1962-Hubel-and-Wiesel.md"
    click Fukushima "https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1980-Kunihiko-Fukushima.md"
    click LeCun "https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1989-Yann-LeCun.md"
    click AlexNet "https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/2012-The-ImageNet-Moment.md"
