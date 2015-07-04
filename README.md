# Laser-Scanner-

stand in code for galvos and PMT until circuit can be made.  

Scanner osc. at 15.63 KHz  galvos need to sync to the rising edge and osc. at 60 Hz .  
Math == how many times should the scanner's rising edge count before executing movement fucntion.
  duration = 1000 * (1/frequency);
  
  PMT is to detect change in light- photo receptor. 
  Averaging function to slim down low frequency changes to be made.
  create interrupt for PMT.
  this will PWM the imaging raster
  
