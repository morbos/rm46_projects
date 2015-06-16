
            rm46 projects
            -------------

0) This dir is a place holder for various RM46 test cases.

1) rm46_ex1
This example has 2 tasks. 1 waits on a timer to expire, the other, on
what is called a suspension object (SO). Its set to turn on and off
LED_3 and LED_2. LED_3 is on the timer task, LED_2 is turned on a the
midpoint of the cycle of LED_3. 

LED_3  1111111111111111111100000000000000000000  (2secs on, 2off)
LED_2  0000000000000000000011111111110000000000  (1sec on, 1off)

It is built using the ravenscar_sfp_rm46 lib
To build the example. type make. (Ensure that the GNAT ARM compiler is
available in your environment).





