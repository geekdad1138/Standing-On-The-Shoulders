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
    click Babbage "[https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1837-Charles-Babbage.md](https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1837-Charles-Babbage.md)" _top
    click Ada "[https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1843-Ada-Lovelace.md](https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1843-Ada-Lovelace.md)" _top
    click Turing "[https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1936-Alan-Turing.md](https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1936-Alan-Turing.md)" _top
    click Shannon "[https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1948-Claude-Shannon.md](https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1948-Claude-Shannon.md)" _top
    click Transistor "[https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1947-The-Transistor-Team.md](https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1947-The-Transistor-Team.md)" _top
    click Intel "[https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1971-Intel-4004-Team.md](https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1971-Intel-4004-Team.md)" _top
    click Dartmouth "[https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1956-The-Dartmouth-Founders.md](https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1956-The-Dartmouth-Founders.md)" _top
    click Rosenblatt "[https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1958-Frank-Rosenblatt.md](https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1958-Frank-Rosenblatt.md)" _top
    click Minsky "[https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1969-Minsky-and-Papert.md](https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1969-Minsky-and-Papert.md)" _top
    click Backprop "[https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1986-The-Backprop-Team.md](https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1986-The-Backprop-Team.md)" _top
    click LSTM "[https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1997-LSTM-Team.md](https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1997-LSTM-Team.md)" _top
    click Hubel "[https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1962-Hubel-and-Wiesel.md](https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1962-Hubel-and-Wiesel.md)" _top
    click Fukushima "[https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1980-Kunihiko-Fukushima.md](https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1980-Kunihiko-Fukushima.md)" _top
    click LeCun "[https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1989-Yann-LeCun.md](https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/1989-Yann-LeCun.md)" _top
    click AlexNet "[https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/2012-The-ImageNet-Moment.md](https://github.com/geekdad1138/Standing-On-The-Shoulders/blob/main/docs/lineage/2012-The-ImageNet-Moment.md)" _top