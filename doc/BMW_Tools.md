# BMW Tools

There is public information about many different BMW hardware and software tools. This page tries to summarize that spread information.

One of the classification criteria used for the tools is the target public for what it was intended and designed:

- Dealer: Intended to be used by car dealers and repair shops. Allows access to resources that the user may not have access to but restrictive enough to minimize possible user induced errors. Usually expose a nice user interface that it is intended to be seen by a large amount of users.
- Engineering: Tools for car development and testing either in the engineering or production phase. Mainly used during early testing and to automate production testing. Give advanced access to car features at the risk of breaking things. User interfaces are not very user friendly because target audience usually has advanced knowledge and are meant to be used by a small amount of users.
- DIY: Tools made by the community not oficially supported by BMW but widely used.

## Hardware

| Name            | Target | Capabilities          | Manufacturer | Model          | FCC ID       | Image                                      |
| --------------- | ------ | --------------------- | ------------ | -------------- | ------------ | ------------------------------------------ |
| Key Reader      | Dealer | Read & write BMW keys | Huf Tools    | MTR 1-125      | PD6MTR01-125 | ![](BMW_Tools_Key_Reader_PD6MTR01-125.png) |
| Key Reader Plus | Dealer | Read & write BMW keys | TeraTron     | KR0304         | QLXKR0304    | ![](BMW_Tools_Key_Reader_QLXKR0304.png)    |
| Key Reader Plus | Dealer | Read & write BMW keys | TeraTron     | KeyReader Plus | QLXKRP       | ![](BMW_Tools_Key_Reader_QLXKRP.png)       |
| ENET            | DIY    | Read & write to cars  | -            |                |              |                                            |
| ICOM Next A     | Dealer | Read & write to cars  |              |                |              |                                            |
| ICOM Next B     | Dealer | Read & write to cars  |              |                |              |                                            |
| ICOM Next D     | Dealer | Read & write to cars  |              |                |              |                                            |
| ISSS Next       |        | Read & write to cars  |              |                |              |                                            |

## Software

| Name  | Target      | Capabilities                      |
| ----- | ----------- | --------------------------------- |
| ETK   |             |                                   |
| KaSIO |             |                                   |
| ISTA  | Dealer      | Diagnosis, updating & programming |
| E-Sys | Engineering | Programming & coding              |
