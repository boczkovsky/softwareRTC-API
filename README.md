softwareRTC API

Design, Program, Test and write API for a softwareRTC running on the atmega328
  * requirements:
    * It shall use timers and interrupts
    * Explain the chosen SFR register setup .
    * it shall implement methods like
      * readhour()
      * readminute()
      * readsecond()
      * setsecond()
      * sethour()
      * setminute()
    * OO or non-OO are graded the same this time
    * For testing ..  Use your good   imagination. Setup tests 
      * explain test
      * explain outcome
    * Inspiration for API.. see
      * https://www.arduino.cc/en/serial/write
      * https://github.com/leomil72/swRTC
      * https://linux.die.net/man/2/gettimeofday