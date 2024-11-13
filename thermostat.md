# Connect to mpj thermostat
 - Communication parameter
   - stopbit=1
   - databit=8
   - boadrate=9600 
   - pwity bit =none(0)
   - comport=device msnsger
 
 
 - register table 
   - reg add---------------reg valve-----------parameter
    - 1---------------2(coling)3(heating)---mode(sensor mode)
    - 2-----------------1(L)2(M)3(H)4(A)--------fan speed
    - 4---------------------15_35----------setpoint(دما اسایش)
    - 5----------------------0_9----------current temperature
    - 7-------------------0(off)1(on)-------------power