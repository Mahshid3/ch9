# ch9
Public class Example5_3{
    Public static void main(String[] args); {

       String str="computer science is a dynamic science";
       String subsrt="science";
       int count;
       count=countSpaces(str);
       System.out.println("string is:"+ str);
       System.out.println("number of blank is:"= count);
       count= substringcount(str,substr);

       System.out.println("string is;"+ str);
       System.out.println("substring is:"+substr);
       System.out.println(" substring iterates"+ count + "times in str");
    }
    
      Public static int countSpaces ( String s)
        {
          int count=0;
          int index=s.indexOf('');

          while(index>=0)
          {
             count++;
             index=s.indexOf('', index + 1);
          }
          return count;
      }

         Public static int substringCount ( String s, String sunstring) {

           int count=0;
           int index=s.indexOf(substring);

            while(index>=0)
            {
               count++;
               index=s.indexOf(substring, index + 1);
             }
             return count;
         }   
       }      


            


           
      

          
