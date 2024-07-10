

class Solution {
     int [] twoSum(int[] nums, int target) {
        List<Integer> result = new ArrayList<>();
        Map<Integer, Integer> map = new HashMap<>();

        for (int i = 0; i < nums.length; i++) {
            int intobj1 = nums[i];
            Integer integerobj1 = intobj1;
            int intobj2 = i;
            Integer integerobj2 = intobj2;
            map.put(integerobj1, integerobj2);
        }

        for (int i = 0; i < nums.length; i++) {
            int complement = target - nums[i];
            int intobj2 = i;
            Integer integerobj2 = i;
            Integer integerobj3 = complement;
            if (map.containsKey(integerobj3) && map.get(complement) != i) {
                Integer compval = map.get(complement);
                result.add(integerobj2);
                result.add(compval);
                break;


            }
   

}
