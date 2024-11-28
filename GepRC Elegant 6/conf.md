# GepRC Elegant 6

## name
name Le_Tic Elegant 6

## feature
feature -AIRMODE
feature TELEMETRY
feature LED_STRIP
feature OSD

## serial
serial 1 2048 115200 57600 0 115200	# T2 VTX
serial 3 64 115200 57600 0 115200	# T4/R4 RX

## beeper
CONFIGURAR <====

## led ===> Estudar e melhorar esta configuracao <=== Copiado do Elegant 5
led 0 7,7::ATOIW:8
led 1 7,8::ATOIW:8
led 2 7,9::ATO:10
led 3 7,10::ATO:10
led 4 7,11::ATO:10
led 5 7,12::ATO:10
led 6 7,13::ATO:10
led 7 7,14::ATO:10
led 8 7,15::ATO:10
led 9 8,7::ATOIW:0
led 10 8,8::ATOIW:0
led 11 8,9::ATOIW:0
led 12 8,10::ATOIW:0
led 13 8,11::ATOIW:0
led 14 8,12::ATOIW:0
led 15 8,13::ATOIW:0
led 16 8,14::ATOIW:0
led 17 8,15::ATOIW:0


## vtxtable
vtxtable bands 5
vtxtable channels 8
vtxtable band 1 BOSCAM_A A CUSTOM  5865 5845 5825 5805 5785 5765 5745 5725
vtxtable band 2 BOSCAM_B B CUSTOM  5733 5752 5771 5790 5809 5828 5847 5866
vtxtable band 3 BOSCAM_E E CUSTOM  5705 5685 5665 5645 5885 5905 5925 5945
vtxtable band 4 FATSHARK F CUSTOM  5740 5760 5780 5800 5820 5840 5860 5880
vtxtable band 5 RACEBAND R CUSTOM  5658 5695 5732 5769 5806 5843 5880 5917
vtxtable powerlevels 4
vtxtable powervalues 14 20 26 36
vtxtable powerlabels 25 100 400 1W+

## master
set acc_calibration = -3,59,-4279,1

set min_check = 1010
set max_check = 1990
set small_angle = 180
set deadband = 2
set yaw_deadband = 2

set pid_process_denom = 2  #??

set osd_vtx_channel_pos = 18820
set osd_canvas_height = 13

set gyro_1_sensor_align = CW270FLIP
set gyro_1_align_pitch = 1800

profile 0

profile 1

profile 2

profile 3

## restore original profile selection
profile 0

rateprofile 0

rateprofile 1

rateprofile 2

rateprofile 3

## restore original rateprofile selection
rateprofile 0

