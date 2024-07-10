class Solution {
    public int missingNumber(int[] nums) {
        Map<Integer, Integer> map = new HashMap<>();
        for (int i = 0; i <= nums.length; i++){
            map.put(i,-1);
            }

        for (int num : nums){
            if (map.containsKey(Integer.valueOf(num))){
                map.put((Integer.valueOf(num)), num);
            }
        }
        for (Integer m :map.keySet()){
            if (map.get(m) == -1){
                return m;
            }
        }

    return -1;}
}
