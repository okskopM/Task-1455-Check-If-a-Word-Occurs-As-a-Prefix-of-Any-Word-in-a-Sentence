class Solution {
    public int isPrefixOfWord(String sentence, String searchWord) {
      final String[] words = sentence.split(" "); 
        for(int i = 0; i < words.length; i++){
            System.out.println(i + " " + words [i]);
            final String isPrefixOfWord = words[i];
            if (words[i].startsWith(searchWord)){
                return i+1;
            }
        }
        return -1;

    }
}  
