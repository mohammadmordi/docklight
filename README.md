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
  ---------------------------------------------------  
 - tern OFF and tern ON and read state 
   - on pout1 02060001000259F8-----RX=02060001000259F8
    - on pout2 020600020002A9F8----RX=020600020002A9F8
    - on pout3 020600030002F838----RX=020600030002F838
    - off pout1 02060001000119F9---RX=02060001000119F9
    - off pout2 020600020001E9F9---RX=020600020001E9F9
    - off pout3 020600030001B839---RX=020600030001B839
    - read pout1 020300010001D5F9--RX=02030200013D84
    - read all pout 0203000100035438---RX=020306000100019845
