# stepin_embeddeb_c
## HOTSEAT
The buttons have to be switched on before the app starts working.
 Potentiometer acts as temperature sensor. It gives signal which is converted by ADC and used to make a PWM signal pf corresponding duty cycle, as seen in the oscilloscope. 
 As potentiometer is varied, message containing detected temperature is shown in serial monitor.
|Code Score|Code Status|Cppcheck|Compile|
|  :--:    |   :--:    |  :--:  | :--:  |
|<img src="https://www.code-inspector.com/project/28622/score/svg" />|<img src="https://www.code-inspector.com/project/28622/status/svg" />|[![Cppcheck](https://github.com/PavanKummarikuntla/M2-Embedded_Hotseat/actions/workflows/CodeQuality.yml/badge.svg)](https://github.com/PavanKummarikuntla/M2-Embedded_Hotseat/actions/workflows/CodeQuality.yml)|[![Compile-Linux](https://github.com/PavanKummarikuntla/M2-Embedded_Hotseat/actions/workflows/Compile.yml/badge.svg)](https://github.com/PavanKummarikuntla/M2-Embedded_Hotseat/actions/workflows/Compile.yml)|

## Contributors List and Summary

PS No. |  Name               |    Features I'D   | Features |
-------|---------------------|-------------------|----------|
40020882 |Pavan Kumar Kummarikuntla  | F1, F2, F3  | Tests if button is on or not, Converts the binary to adc, Displays the temperature on the serial monitor | 
  

## Challenges Faced and How Was It Overcome
| No. | Challenge | Solution
|-----|-----------|--------
|1. | On the simulide latest version some sources are not available| By the help of connect class solved |
|2. | issues in implementation | fixed them by making template in order
|3. | Issues in workflows | fixed them by updating the path to all files correctly
