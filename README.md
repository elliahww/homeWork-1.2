# homeWork-1.2
пакет com.company;

импорт java.util.Random;

публичный класс Main {

    public static void main(String[] args) {
        System.out.println(студент(7, 10));
        System.out.println(студент(15, -30));
        System.out.println(студент(22, 10));
        System.out.println(студент(43, 50));
        System.out.println(студент(7, 10));


        System.out.println("возраст" + " " + generateRandomAge);
    }

    public static String student(int age, int temperature) {

        если ((возраст> 20 && возраст < 45) && (температура> -20 && температура < 30)) {
            return ("Можно идти гулять ");
 } else if ((возраст < 20) && (температура >= 0 && температура < 28)) {
            return (" Можно идти гулять ");
 } else if ((возраст > 45) && (температура > -10 && температура < 25)) {
            return ("Можно идти гулять ");
 } else {
            return ("оставайтесь дома");
        }
    }

    public static int generateRandomAge;
    Random random = новый Random();
    int age = random.nextInt(100);
     возраст возврата;
    }

