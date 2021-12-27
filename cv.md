# Alexander Denisov
---
## Contact information:
---
* **Location:** Kazan city, Tatarstan  Republic, Russia
* **Phone:** +7(843) 526-73-10
* **E-mail:** <alexden@npk-va.com>
## About Me
---
I am 35 years old. I've been working for the same company for 13 years. I went from an engineer to the head of the software department. I develop software for industrial automation and control systems.

Currently, the trend in the development of production technologies is directed towards remote control and monitoring of technological processes. This control can be achieved through the use of **WEB-technologies**,
the most common worldwide among ordinary users. Therefore, my main goal is to gain knowledge in the field of **front-end** development.
## Skills:
---
`Systems of industrial automatization and control` `Team management` `DCS` `Honeywell` `Siemens` `Emerson` `Simatic PCS 7` `Experion PKS` `DeltaV` `Modbus` `Profibus` `C/C++` `Matlab` `VBS` `SCL` `LAD` `TIA Portal` `WinCC` `WinCC OA` `PLC` `SCADA` `HTML5` `CSS3` `VS Code` `Git` `JavaScript Basic`
## Code example:
---
```
    for (COUNT = 1; COUNT <= ITER; COUNT++)
    {
	    Qm_old = Qm;
	    Re_old = Re;
        // expiration coefficient in the first approximation
	    A_ist = powf(19000.0*Betta / Re, 0.8);																				
	    C = 0.5961 + 0.0261*powf(Betta, 2.0) - 0.216*powf(Betta, 8.0) + 
	    0.000521*powf(1.0e6*Betta/Re, 0.7) + 
	    (0.0188 + 0.0063*A_ist)*powf(Betta, 3.5)*powf(1.0e6/Re, 0.3) + 
	    (0.043 + 0.08*exp(-10.0*L1) - 0.123*exp(-7.0*L1))*(1.0 - 0.11*A_ist)*powf(Betta, 4)/( 1.0 - powf(Betta, 4.0))-
	    0.031*(M1-0.8*powf(M1, 1.1))*powf(Betta, 1.3) + M2;												
        // roughness coefficient
	    lgRe = log10(Re);
        // mass flow rate kg/s
	    Qm = (0.25*Pi*powf(dm, 2.0))*Ksh*Kp*E*C*eps*powf(2.0*RO*DPress, 0.5);		
	    Re = (4.0/Pi)*(Qm /(DT*MU));
	    delta = fabs((Qm-Qm_old)/Qm);
	
	    if (delta < 0.000001)
	    {
		    break;
	    }
    }
```
## Education:
---
* **Kazan Federal University**
  * Institute of Physics
## Courses:
---
  * **EXP-50R500RU** _Experion PKS: Fundamentals - Configuration, Graphics Builder and Control Strategy Implementation_
  * **7009** _DeltaV Implementation I_
## Languages:
---
* **Russian** - native speaker
* **English** - A1
