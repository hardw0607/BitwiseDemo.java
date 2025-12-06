# BitwiseDemo.java
BitwiseDemo
public class BitwiseDemo {
    public static void main(String[] args) {
        int a = 29; // 11101 in binary
        int b = 15; // 01111 in binary

        // Bitwise AND
        int andResult = a & b; // 13 (01101 in binary)
        System.out.println("Bitwise AND of " + a + " and " + b + " is: " + andResult);

        // Bitwise OR
        int orResult = a | b; // 31 (11111 in binary)
        System.out.println("Bitwise OR of " + a + " and " + b + " is: " + orResult);

        // Bitwise XOR
        int xorResult = a ^ b; // 18 (10010 in binary)
        System.out.println("Bitwise XOR of " + a + " and " + b + " is: " + xorResult);

        // Bitwise NOT
        int notResult = ~a; // -30 (inverts all bits)
        System.out.println("Bitwise NOT of " + a + " is: " + notResult);

        // Left Shift
        int leftShiftResult = a << 2; // 116 (1110100 in binary)
        System.out.println("Left Shift of " + a + " by 2 is: " + leftShiftResult);

        // Right Shift
        int rightShiftResult = a >> 2; // 7 (00111 in binary)
        System.out.println("Right Shift of " + a + " by 2 is: " + rightShiftResult);
    }
}
//output
<img width="714" height="188" alt="Screenshot 2025-12-06 104227" src="https://github.com/user-attachments/assets/a2bce931-c907-48d8-ad28-c70c9c9a3c76" />

