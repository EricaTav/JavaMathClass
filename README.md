JavaMathClass
=============

Alojamento de código respectivo á Classe Math do Java
=============

public class ComprimentoCirculo {
   public static void main(String[] args) {
        float raio = 2.4f;
       double comprimento = 2 * raio * Math.PI;
        System.out.println(comprimento);
   }
}

============

public class MenorMaior {
    public static void main(String[] args) {
        float precoProdutoA[] = { 11.2f, 15.12f };
        float precoProdutoB[] = { 19.7f, 20 };
       System.out.println("O maior preço do produto A é "
                    + Math.max(precoProdutoA[0], precoProdutoA[1]));
       System.out.println("O menor preço do produto B é "
                   + Math.min(precoProdutoB[0], precoProdutoB[1]));
   }
}

===========

public class PotenciasRaizes {
    public static void main(String[] args) {
        System.out.println("1 MB tem " + Math.pow(2, 10) + " KB");
        System.out.println("A raiz quadrada de 121 é " + 	Math.sqrt(121)
            + " e a raiz cúbica de 1331 também é " + 	Math.cbrt(1331));
    }

===========

public class Exemplo {
    public static void main(String[] args) {
        float nr = 0.1f;
        System.out.println("Resultado 1: " + Math.log(nr+1));
        System.out.println("Resultado 2: " + Math.log1p(nr));
    }
}

===========

public class Exemplo {
    public static void main(String[] args) {
        float nr = -5.75f;
        System.out.println("Absoluto: " + Math.abs(nr) +
                "\nInteiro mais baixo: " + Math.ceil(nr) +
                "\nInteiro mais alto: " + Math.floor(nr) +
                "\nDouble mais próximo: " + Math.rint(nr) +
                "\nArredondamento: " + Math.round(nr));
    }
}

===========

public class Hipotenusa {
    public static void main(String[] args) {
        double ponto1 = 30;
        double ponto2 = 40;
        System.out.println("A distancia entre o "
                + ponto1 + " e o " + ponto2 + " é "
                + Math.hypot(ponto1, ponto2));
    }
}

===========

public class Exemplo {
    public static void main(String[] args) {
        int limiteInferior = 5;
        int limiteSuperior = 10;
        int alcance = limiteSuperior - limiteInferior;
        double nrRandomico = Math.random();
        System.out.println("O número randómico escolhido entre 5 e  10 foi "
                + Math.round(limiteInferior + nrRandomico * alcance));
    }
}


