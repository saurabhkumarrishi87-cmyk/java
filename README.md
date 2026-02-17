public class hollow_rectangle {
    public static void hollow_rectangle(int tolRows, int tolCols) {
        int i, j;
        // Outer loop for rows
        for (i = 1; i <= tolRows; i++) {
            // Inner loop for columns
            for (j = 1; j <= tolCols; j++) {
                // Boundary cells
                if (i == 1 || i == tolRows || j == 1 || j == tolCols) {
                    System.out.print("*");
                } else {
                    System.out.print(" ");
                }
            }
            System.out.println();
        }
    }

    public static void main(String args[]) {
        hollow_rectangle(4, 5);
    }
}# java
