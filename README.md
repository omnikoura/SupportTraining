public class SupportTraining{

 public static void main(String[] args){
     String msgone = "SupportTraining";
     String msgtwo = "Support";
     String msgthree = "Training";
   for(int x=1; x<=100; x++){
     if(x % 15 == 0)
      {
        System.out.print(msgone);
      }
     elseif(x % 3 == 0)
       {
         System.out.print(msgtwo);
       }
     elseif(x % 5 == 0)
       {
         System.out.print(msgthree);
       }
     else
       {
         System.out.print(x);
       }
     }  // Loop
   }  // Main
 }  // Class
