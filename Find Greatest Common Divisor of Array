class Solution {
public:
    int findGCD(vector<int>& nums) {
        int n=nums.size();
        sort(nums.begin(),nums.end());
        int  small,large,product=0;
        small=nums[0];
        large=nums[n-1];
        for(int i=1;i<=small;i++)
        {
            if(large%i==0 and small%i==0)
              product=i;
        }
        return product;
    }
};
//please add comments for help!
