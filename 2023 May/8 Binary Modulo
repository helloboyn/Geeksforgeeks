class Solution{
    public:
        int modulo(string s,int m)
        {
           long long int ans=0;
           long long int ex=1;
           int n=s.size();
           for(int i=n-1;i>=0;i--)
           {
               int x=s[i]-'0';
               
               ans=(ans+x*ex)%m;
               ex=(ex*2)%m;
           }
           return ans%m;
        }
};
