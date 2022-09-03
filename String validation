/***import java.util.regex.Pattern;
 
class Main
{
    private static Pattern p = Pattern.compile("^[a-zA-Z]*$");
 
    public static boolean isAlpha(String s) {
        return p.matcher(s).find();
    }
 
    public static void main(String[] args)
    {
        String s = "$";
        System.out.println("IsAlpha: " + isAlpha(s));
    }
}**/


//2ND METHOD
/**public class Main {

    public static void main(String[] args) {

        char c = 'a';

        if( (c >= 'a' && c <= 'z') || (c >= 'A' && c <= 'Z'))
            System.out.println(c + " is an alphabet.");
        else
            System.out.println(c + " is not an alphabet.");
    }
}**/

////3rd method
/**class Main
{
    public static boolean isAlpha(String s)
    {
        if (s == null) {
            return false;
        }
 
        for (int i = 0; i < s.length(); i++)
        {
            char c = s.charAt(i);
            if (!(c >= 'A' && c <= 'Z') && !(c >= 'a' && c <= 'z')) {
                return false;
            }
        }
        return true;
    }
 
    public static void main(String[] args)
    {
        String s = "ABCD";
        System.out.println("IsAlpha: " + isAlpha(s));
    }
}**/


////4th method
//codition if input is null it is not an string
//(str != null) && (!str.equals(""))&& (str.matches("^[a-zA-Z]*$"))
//(str != null) && (!str.equals(""))&& (str.matches("^[a-zA-Z]+"))
import java.util.*;
public class Main
{
   public static void main(String args[]) 
   {
      Scanner sc = new Scanner(System.in);
      System.out.println("Enter your name: ");
      String str = sc.next();
      if(str != null && str.matches("^[a-zA-Z]*$"))
         System.out.println("Given string is a proper name.");
      else
         System.out.println("Given string is a proper string is not a proper name.");
   }
}
