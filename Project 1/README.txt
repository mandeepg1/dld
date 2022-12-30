In this project I had to create a seven-segment display driver.
In my 8421 BCD dec_driver I made sure to create the variables w,x,y,z as they correspond to the inputs (0000 to 1001).
I made sure each of the variables connect to the seven inputs.
Once the wires were connected properly and in the right spot I made sure there wasn't any errors or red wires.
After that, I connect the dec_counter to the driver in the main and started to connect each wire to the corresponding letter.
Then I tested it and it outputted 0 to 9 and repeated.

For the bonus, I made sure to add 2 of drivers, 2 dec_counters, and 1 one-tick clock.
After setting up the right side of one of the seven-segment displays I took the output of the dec_counter and connected it to the other dec_counter.
This was to allow the one side to finish going through 0 to 9 and allowed the other one to follow after so hence it would go through all 00 to 99 and repeat. 