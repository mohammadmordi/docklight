# step by step toturial for connetion with modbus devices:
- 3-poll switch mpj
    - device configuration connetion:
        - stopbit: 1
        - paritybit: none(0)
        - databit: 8
        - boadrate: 9600

- Registers:
    - address: 1,2,3(hex) map to poll 1,2,3
    - values: 1 means OFF,2 means ON

