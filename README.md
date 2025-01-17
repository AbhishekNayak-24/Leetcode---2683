# Leetcode---2683
Neighboring Bitwise XOR
// CODE IN JAVA
public class Solution {
    public boolean doesValidArrayExist(int[] derived) {
        int xorSum = 0;
        for (int num : derived) {
            xorSum ^= num;
        }
        return xorSum == 0;
    }
}
