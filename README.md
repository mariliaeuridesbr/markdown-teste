# markdown-teste
![gatinho](https://media.discordapp.net/attachments/765443398629982208/779189801026322432/unknown.png)

> Citação

Esse é um parágrafo  
Exemplo de quebra de linha
## Lista não ordenada:
* **negrito**
* *italico*
* ~~riscado~~
* **_negrito e itálico_**
* __*negrito e itálico 2*__
* ~~**_negrito itálico e riscado_**~~
* [link](http://www.google.com)
* [link com variavel][variavel-link]

## Lista ordenada:

1. Primeiro item
    - Subitem :)
2. Segundo item
3. Terceiro item

- - -

## Tabelas:

| Nome | Idade |
| ---- | :---: |
| Gatinha | 2 |
| Bebel | 3 |
| Daisy | 5 |

- - -
## Códigos:

### Javascript
```javascript
class User extends Model{
    static init(sequelize){
        super.init({
            name: DataTypes.STRING,
            email: DataTypes.STRING,
        }, {
            sequelize
        })
    }
}
```
### Java
```java
public class Professor extends Colaborador {
	private int numeroSindicato;
	
	public void setNumeroSindicato(int num) {
		numeroSindicato = num;
	}
	
	public int getNumeroSindicato() {
		return numeroSindicato;
	}
	
	public String getMatricula() {
		return super.getMatricula() + numeroSindicato;
	}
}
```
- - -

## Mais tipos de imagem

### Imagem com link

[![Gatinho](https://media.discordapp.net/attachments/765443398629982208/779189801026322432/unknown.png)](http://www.google.com)

### Imagem com link em variável


[![Gatinho](https://media.discordapp.net/attachments/765443398629982208/779189801026322432/unknown.png)][variavel-link]

> 
[variavel-link]: http://www.google.com