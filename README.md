# lista2
package c125.l3;

public class Principal {
    public static void main(String[] args) {

    Pessoa p1 = new Pessoa("Giovanna", 1234, 2);

    Endereco end1 = new Endereco("Rua Juca Castelo", "Bairro Maristela", 530);
    Endereco end2 = new Endereco("Rua Dr Jose de Abreu", "Bairro Maristela", 209)

    p1.addEndereco(end1);
    p1.addEndereco(end2);
    // p1.addEndereco(end3);

    p1.mostraInfo();
}
}
