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
    
    %% Lineage D: The Visual/Biological Path
    Hubel[1962: Hubel & Wiesel]
    Fukushima[1980: Kunihiko Fukushima]
    LeCun[1989: Yann LeCun]

    %% Connections showing the "Collision"
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
    Hubel --> Fukushima
    Fukushima --> LeCun
    Backprop --> LeCun

    %% Clickable Links (Fixed for GitHub)
    click Babbage "/docs/lineage/1837-Charles-Babbage.md" _top
    click Ada "/docs/lineage/1843-Ada-Lovelace.md" _top
    click Turing "/docs/lineage/1936-Alan-Turing.md" _top
    click Shannon "/docs/lineage/1948-Claude-Shannon.md" _top
    click Boole "/docs/lineage/1847-George-Boole.md" _top
    click Transistor "/docs/lineage/1947-The-Transistor-Team.md" _top
    click Intel "/docs/lineage/1971-Intel-4004-Team.md" _top
    click Dartmouth "/docs/lineage/1956-The-Dartmouth-Founders.md" _top
    click Rosenblatt "/docs/lineage/1958-Frank-Rosenblatt.md" _top
    click Minsky "/docs/lineage/1969-Minsky-and-Papert.md" _top
    click Backprop "/docs/lineage/1986-The-Backprop-Team.md" _top
    click Hubel "/docs/lineage/1962-Hubel-and-Wiesel.md" _top
    click Fukushima "/docs/lineage/1980-Kunihiko-Fukushima.md" _top
    click LeCun "/docs/lineage/1989-Yann-LeCun.md" _top