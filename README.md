# indiceLiquidezImediata
O índice de liquidez imediata procura entender a capacidade de uma organização cumprir com suas obrigações e realizar os pagamentos imediatamente. Isso é bom para avaliar se a empresa conseguiria lidar com emergências financeiras.

```
public class liquidezImediata {
	public static void main(String[] args) {
		double disponibilidades = 5889000;
		double passivoCirculante = 27503000;

		double liquidezImediata;

		liquidezImediata = disponibilidades / passivoCirculante;

		System.out.println("O índice calculado em liquidez Imediata é?  " + 
				liquidezImediata);
	}

}
