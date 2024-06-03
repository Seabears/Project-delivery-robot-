# Project-delivery-robot-

Stm32H735G-DK  

Use uart1  
tx pb14 d1  
rx pb15 d0

connect to hc-06  
baud rate = 9600

모터드라이버  
pg5 ARD_D7- IN1(GPIO OUT)  
pe3 ARD_D8 - IN2 (GPIO OUT)  
pb7 ARD_D9  - TIM4_CH2 (ENA)  
pg3 ARD_D2 -IN3 (GPIO OUT)  
pg4 ARD_D4 -IN4 (GPIO OUT)  
pe14 ARD_D5 - TIM1_CH4 (ENB)  
pc0 ARD_A0_Pin - 오른쪽 적외선 센서 (GPIO IN)  
ph2 ARD_A1_Pin - 왼쪽 적외선 센서 (GPIO IN)  
pf14 ARD_D15_Pin - 아두이노(RGB 센서) IN  
E5V - RGB  
3V- 오른쪽  
아두이노 3V 왼쪽  
VIN - STM32 전원(아두이노의 5V)  
