# JAVA

public class array{
    public static void main(String[] args) {

        m();
        m(10);
        m(10,20);

        m2("12","asc","d34");

        m2(new String[]{"a","b"});
    }

    public static void m(int... args){
        System.out.println("m可执行");
    }

    public static void m2(String... args){
        for(String s:args)
            System.out.println(s);
    }

}
