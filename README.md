# method-overloading
public class Poly{
    void add(int a,int b,int c){
        System.out.println("sdfhohg");
        
    }
    void add(float a, float b){
        System.out.println("Float:"+(a+b));
    }
    void add(int a,int b,int c){
        System.out.println("Three Values:"+(a+b));
    }
}
class Main3{
    public static void main(String[] args){
        Poly p=new Poly();
        p.add(a:1,b:2);
        p.add(a:3.5f,b:4.5f);
        p.add(a:)
    }
}

