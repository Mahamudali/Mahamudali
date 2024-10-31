/* Report on how much will be spent on holiday gifts */
#include <stdio.h>
main()
{ 
	float gift1, gift2, gift3, gift4; /*variables to hold costs */
	float total; /* variable to hold total amount */
	
/* Ask for each gift amount */
printf("How much do you want to spend on Mom? ");
scanf(" %f", &gift1);
printf("How much do you want to spend on Dad? ");
scanf(" %f", &gift2);
printf("How much do you want to spend on Sister? ");
scanf(" %f", &gift3);
printf("How much do you want to spend on Brother? ");
scanf(" %f", &gift4);

total = gift1+gift2+gift3+gift4;
printf("/nThe total you will be spending is $%.2f", total);
return 0; 
}
