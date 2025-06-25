# IMU-PIXHAWK-ARDUINO

SCALED_IMU2 parametresi ile xgyro,ygyro,zgyro yani AÇISAL HIZ verileri çeikilr.

ATTITUDE parametresi ile xacc,yacc,zacc yani DOĞRUSAL İVME verileri çekilir.

Alan	Açıklama	Birim
xacc	X ekseni ivme	mg 
yacc	Y ekseni ivme	mg
zacc	Z ekseni ivme	mg
xgyro	X ekseni açısal hız	
ygyro	Y ekseni açısal hız	
zgyro	Z ekseni açısal hız	

Qgroundcontrolde yukarıdaki verileri mavlink parametreler kısmında görebilirsin.

Açısal ivme doğrudan Pixhawk’tan gelmez, açısal hızın türeviyle hesaplanır.
DOĞRUSAL İVME Pixhawktan doğrudan gelir.

