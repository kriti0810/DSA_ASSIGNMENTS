class Solution {
public:
    vector<int> targetIndices(vector<int>& nums, int target) {
        vector<int> ans;
        
        int index = 0;
        int frequency = 0;
        
        for(int i = 0; i < nums.size(); i++){
            if(nums[i] < target)
                index++;
            else if(nums[i] == target)
                frequency++;
        }
        
        while(frequency > 0){
            ans.push_back(index);
            frequency--;
            index++;
        }
        return ans;
    }
};
