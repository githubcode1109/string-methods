# string-methods
class StringMethods {
    public static void main(String[] args) {
        String str="Helloworld! Welocme to java programming. ";
        //length
        int length=str.length();
        System.out.println(length);
        //charAt(index)
        System.out.println(str.charAt(6));
        //substring(start,endingindex)
        System.out.println(str.substring(3,15));
        //toUppercase()
         System.out.println(str.toUpperCase());
         //lowercase
          System.out.println(str.toLowerCase());
         //contains
          System.out.println(str.contains("java"));
       
    }
}
