|                  |   VM <-> VM   |   VM -> Host   |   VM <- Host   |   VM -> LAN   |   WM <- LAN   |
| ---              |     :---:     | :---:          |      :---:     |     :---:     |     :---:     |
| Not attached     |---------------|----------------|----------------|---------------|---------------|
| Nat              |---------------|++++++++++++++++|  Port Forward  |+++++++++++++++| Port forward  |
| NAT Network      |+++++++++++++++|++++++++++++++++|  Port Forward  |+++++++++++++++| Port forward  |
| Bridged          |+++++++++++++++|++++++++++++++++|++++++++++++++++|+++++++++++++++|+++++++++++++++|
| Internal Network |+++++++++++++++|----------------|----------------|---------------|---------------|
| Host-only        |+++++++++++++++|++++++++++++++++|++++++++++++++++|---------------|---------------|
