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
    Dartmouth --> Rosenblatt
    Rosenblatt --> Minsky
    Minsky --> Backprop

    %% Clickable Links (Fixed for GitHub)
    click Babbage "/docs/lineage/1837-Charles-Babbage.md" _top
    click Ada "/docs/lineage/1843-Ada-Lovelace.md" _top
    click Turing "/docs/lineage/1936-Alan-Turing.md" _top
    click Shannon "/docs/lineage/1948-Claude-Shannon.md" _top
    click Transistor "/docs/lineage/1947-The-Transistor-Team.md" _top
    click Intel "/docs/lineage/1971-Intel-4004-Team.md" _top
    click Dartmouth "/docs/lineage/1956-The-Dartmouth-Founders.md" _top
    click Rosenblatt "/docs/lineage/1958-Frank-Rosenblatt.md" _top
    click Minsky "/docs/lineage/1969-Minsky-and-Papert.md" _top
    click Backprop "/docs/lineage/1986-The-Backprop-Team.md" _top