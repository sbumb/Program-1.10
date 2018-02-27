# Program-1.10
Intro to Java Programming, Comprehensive Version, 10th Edition, Y. Daniel Liang

Question:

        (Average speed in miles) Assume a runner runs 14 kilometers in 45 minutes 
        and 30 seconds. Write a program that displays the average speed in miles 
        per hour. (Note that 1 mile is 1.6 kilometers.)
        
Code:

        public class s_1_10 {
	        public static void main (String args[]){
		
		      double kilometers = 14.0;
		      double miles = kilometers/1.6;
		
		      double rate = (45.5 * 60.0 + 30.0)/(60.0 * 60.0);
		      double mph = miles/rate;
		
		    System.out.println(mph);
		
      }
    }
