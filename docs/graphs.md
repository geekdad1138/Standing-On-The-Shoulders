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

    %% Clickable Links (Relative Paths)
    click Babbage "./lineage/1837-Charles-Babbage.md" "Read about Babbage"
    click Ada "./lineage/1843-Ada-Lovelace.md" "Read about Lovelace"
    click Turing "./lineage/1936-Alan-Turing.md" "Read about Turing"
    click Shannon "./lineage/1948-Claude-Shannon.md" "Read about Shannon"
    click Transistor "./lineage/1947-The-Transistor-Team.md" "Read about The Transistor"
    click Intel "./lineage/1971-Intel-4004-Team.md" "Read about Intel 4004"
    click Dartmouth "./lineage/1956-The-Dartmouth-Founders.md" "Read about Dartmouth"
    click Rosenblatt "./lineage/1958-Frank-Rosenblatt.md" "Read about Rosenblatt"
    click Minsky "./lineage/1969-Minsky-and-Papert.md" "Read about Minsky"
    click Backprop "./lineage/1986-The-Backprop-Team.md" "Read about Backprop"