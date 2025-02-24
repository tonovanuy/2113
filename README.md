interface Operation {
    int perform(int a, int b);
}

class Main {
    public static void main(String[] args) {
        Operation sum = (a, b) -> a + b;
        Operation difference = (a, b) -> a - b;
        Operation product = (a, b) -> a * b;
        
        System.out.println(sum.perform(5, 3));
        System.out.println(difference.perform(10, 4));
        System.out.println(product.perform(6, 7));
    }
}
