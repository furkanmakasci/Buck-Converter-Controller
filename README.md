# Buck-Converter-Controller
Look the asynchronous buck converter type 2 compensator which my 2nd attemp of designing a buck converter after this project, has worse efficiency than XL4016 modules which 15Vto2V %67-75, 15Vto5V %80-95. Also, it has better regulation than XL4016 modules.

Analog Buck Converter Controller with Current Limiting Feature

200 kHz buck controller circuit, used OPAx197s. 7805 used for reference voltage(to supply opamps). Also, frequency of triangle wave generater first was implemented for 12V, so you can use 12V regulator and 1 to 120 gain for reading current or voltage divider for feedback to get higher voltage outputs... Frequency 209 kHz --> 12V, 230 kHz --> 5V.

...

Drive part is up to you, also you can add a derivative control part. It was good enough for my application...

I want to implement a part for synchronous buck later..

![](buck-controller.jpg)
