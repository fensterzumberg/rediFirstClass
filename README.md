# rediFirstClass

public class ExerciseIntro {
        public static void main(String[] args) {
            square(1, 3);
            square(5, 6);
        }

        public static int square(int x, int y) {
            for(int i = x; i<=y; i++) {
                System.out.println(i);
                return i*i;
            }
        }
}
