# RepoEjemplo
# Aprendiendo Markdown

Mis primeros *pasos* en **Markdoen**, que es un un formato de marcado de ***archivos de texto***.

A continuacion una ___lista___:

* Item 1
* Item 2
    * Item 2.1
    * Item 2.2
* Item 3

A continuacion una __tabla_:

| Codigo | Nombre | Precio |
| :-: | :-: | -: |
| 1 | TV | 553.99 |
| 2 | Computador | 1687.23 |
| 3 | Celular | 791.51 |

A continuacion un _enlance_ o *link*:

[Diario el pais de España](https://elpais.com/america/)

A continuacion una __imagen__:

![Logo de Enner](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTunZcM0YRc04yLKyCGTgdT4MJ2CBoxx_9ceA&s)

# Titulo nivel 1
## Titulo nivel 2
### Titulo nivel 3

A continuacion el **codigo de un programa**:

```
import java.util.Scanner;
public class Saludo2 {
	public static void main (String[] args){
		Scanner sc = new Scanner (System.in);
		String nombre;
		System.out.print("Dime tu nombre: ");
		nombre = sc.nextLine();
		System.out.print("Hola " + nombre);
		System.out.println(", encantado de conocerte!");
		}
}

