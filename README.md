# Thirdrepository
i developed this program using c.
#include<stdio.h>
struct displayAccount{
int price;
int gst;
int discount;
};
int main()
{
   struct displayAccount a1;

   printf("Enter price: \n");
   scanf("%d",&a1.price);

   printf("Enter gst: \n");
   scanf("%d",&a1.gst);

   printf("Enter discount: \n");
   scanf("%d",&a1.discount);

   printf("price:%d gst:%d discount:%d",a1.price,a1.gst,a1.discount);

   return 0;
}
