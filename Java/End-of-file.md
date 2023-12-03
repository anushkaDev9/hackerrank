public class Solution {
    public static void main(String[] args) {
       Scanner scan=new Scanner(System.in);
       int lineNum=0;
       while (scan.hasNext()){
           String sentence=scan.nextLine();
            lineNum++;
            System.out.println(lineNum+" "+sentence);
       }
    }
}
