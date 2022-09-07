# calling-to-new-class- 
// calling from new class 

class HelloWorld {

    public static void main(String[] args) {

        hcl jk= new hcl();

        jk.add();

        jk.multi();

        jk.divid();

        System.out.println(jk.a);

        System.out.println(jk.b);

        

    }

}

class hcl{

    int a=4;

    int b=8;

    void add(){

        System.out.println(a+b);

    }

    void multi(){

        System.out.println(a*b);

    }

    void divid(){

        System.out.println(b/a);

    }

}
