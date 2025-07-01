 public class StringLab {
   public static void main(String[] args) {
        String str = " Welcome to the Java String Lab! ";
        //
        System.out.println("Length: " + str.length())
           System.out.println("Character at index 7: " + str.charAt(7));
  System.out.println("Substring 'Java': " + str.substring(18, 22));
   System.out.println("Uppercase: " + str.toUpperCase());
        System.out.println("Lowercase: " + str.toLowerCase());
          System.out.println("Index of 'Java': " + str.indexOf("Java"));
            System.out.println("Contains 'Lab': " + str.contains("Lab"));
             System.out.println("Replace 'Java' with 'Java Programming': " + str.replace("Java",
              String[] words = str.trim().split("\\s+");
        System.out.println("Words:");
        for (String word : words) {
            System.out.println(word)
            {
               System.out.println("Trimmed: '" + str.trim() + "'")
                System.out.println("Equals 'java string lab!': " + str.equals("java string lab!"));
        System.out.println("EqualsIgnoreCase 'java string lab!': " + str.equalsIgnoreCase(
          }
       }   
