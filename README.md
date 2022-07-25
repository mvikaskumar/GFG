Program to check weather a string is palindrome pr not.(GFG)

class Solution {
    int isPalindrome(String S) {
        // code here
        int count;
        String NewS="";
        for(int i=S.length()-1;i>=0;i--){
            NewS+=S.charAt(i);
        }
        if(S.equals(NewS)){
            count=1;
        }
        else{
            count=0;
        }
        
    return count;
    }
}
