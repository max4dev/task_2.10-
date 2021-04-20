# task_2.10-

public class Main {

    public static void main(String[] args) {

        int numbers[] = {1, 2, 2, 3, 4, 5, 4, 6};

        for (int i = 0; i < numbers.length - 1; i++) {
            if (numbers[i] == numbers[i + 1]) {
                System.out.println("В массиве найдены одинаковые рядом стоящие числа: " + numbers[i] + " и " + numbers[i + 1]);
            }
        }
    }
}
