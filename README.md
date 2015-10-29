public class SupportTraining{

 public static void main(String[] args){
     String msgone = "SupportTraining";
     String msgtwo = "Support";
     String msgthree = "Training";
   for(int x=1; x<=100; x++){
     if(x % 15 == 0)
      {
        System.out.printIn(msgone);
      }
     elseif(x % 3 == 0)
       {
         System.out.printIn(msgtwo);
       }
     elseif(x % 5 == 0)
       {
         System.out.printIn(msgthree);
       }
     else
       {
         System.out.printIn(x);
       }
     }
   }
 }  
