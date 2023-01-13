class Solution {
public:
    int trailingZeroes(int n) {
        int count=0;
        long long int fact=1;
      for(int i=1;i<=n;i++)
      {
          if(i%5==0 && i%25!=0  && i%125!=0  && i%625!=0  && i%3125!=0 )
          count=count+1;
          else if(i%25==0  && i%125!=0  && i%625!=0  && i%3125!=0)
          count=count+2;
          else if(i%125==0  && i%625!=0  && i%3125!=0)
          count=count+3;
          else if(i%625==0 && i%3125!=0)
          count=count+4;
          else if(i%3125==0)
          count=count+5;
      }
     return count;
}
};
