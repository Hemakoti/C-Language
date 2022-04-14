/*Hey There I'm Hemakoti Bonthada...!
In This Code We Are Going to Check Whether The Entred Pin Is Correct Or Not
For That We Are Using While Loop To Enter Maximum Number of Incorrect Pins For 5 Times and If We Enter Correct Pin Loop Will Automatically Closes
This is Only For Intergers
*/
#include <stdio.h>
#include <stdlib.h>

int
main ()
{
  const int pass = 1122;
  int user;
  int i = 1;
  while (i <= 5)
    {
      puts ("\nEnter A 4 Digit Pin");
      scanf ("%d", &user);
      if (user != pass)
	{
	  puts ("\nUh Entered Incorrect Pin Bustard");
	  if (i <= 4)
	    puts ("\nHey Fucker Just Enter a Vaild Pin");
	  if (i == 4)
	    puts ("\nThis Is Your Last Chance To Enter Your Pin Fucker");
	  i++;
	  if (i == 6)
	    {
	      puts
		("\nYou Entered Incorrect Pin More Than 4 Times Fucker, So Just Fuck OFF");
	    }
	  continue;
	}
      else
	{
	  puts ("You Entered Correct Pin Fucker\n");
	  break;
	}
    }
  return 0;
}
