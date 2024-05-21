# Function


https://docs.oracle.com/javase/10/docs/api/java/util/function/Function.html


public interface Function<T, R> {

R apply(T t);

}

Problema exemplo

Fazer um programa que, a partir de uma lista de produtos, gere uma nova lista contendo os nomes dos produtos em caixa alta.

List<Product> list = new ArrayList<>();


list.add(new Product("Tv", 900.00));

list.add(new Product("Mouse", 50.00));

list.add(new Product("Tablet", 350.50));

list.add(new Product("HD Case", 80.90));

#Nota sobre a função map

A função "map" (não confunda com a estrutura de dados Map) é uma função que aplica uma função a todos elementos de uma stream.

• Conversões:

• List para stream: .stream()

• Stream para List: .collect(Collectors.toList())
