# circuit-breakers_HTH_2K25
                +5V  GND
                 |     |
        +--------+-----+--------------------+
        |                              ____|____
        |                             |         |
      .-.-. IR1                      .-.-. IR2  |
      |   | VCC ---------------------|   | VCC  |
      |   | GND ---------------------|   | GND  |
      |   | OUT ---- D2              |   | OUT ---- D3
      '-'                           '-'  
                                          Arduino UNO
                           D5 --[220Ω]-->|> LED Free (to GND)
                           D6 --[220Ω]-->|> LED Busy (to GND)

                       Servo
                   (SG90/MG90S)
                 Signal ---- D9
                 +5V    ---- 5V (prefer external 5V if possible)
                 GND    ---- GND (COMMON GND with Arduino)

