# Ejercicio Angular v13

Descripción:
- Generar un nuevo proyecto de Angular
  - Comando ng new <project_name>
  - Recuerde que debe tener previamente instalado node y angular CLI
- Genere, adicionamentel al app component, dos componentes de nombre componente1 y
componente2
  - ng generate component <component_name>
  - Recuerde esta ubicado en el folder del proyecto cuando corra estos comandos
- Indique una propiedad numérica en cada componente nuevo, y decorela con @Input() de
manera que sea posible ser sobreescrita desde un componente padre
- En el componente padre declare una propiedad tambien numérica que será la que
sobreescribirá la propiedad de los dos componentes anteriores ( hijos ).  En el componente padre, utilice un control <input> ( html ) para poder alterar el valor de esta
propiedad. Utilice [(ngModel)] para poder alterar la propiedad directamente
  - Recuerde realizar los imports respectivos al modulo para que esta directiva funcione
  - Utilice de referencia el proyecto visto en clase. 
- Utilizando la implementacion de OnChanges capture, en los componentes hijos, todos los cambios generados a esta variable desde el input del padre. 
- Para uno de los componentes hijos, imprimir el valor de la variable numérica alterada solamente si ha cambiado a ser un numero multiplo de 5. 
- Para uno de los componentes hijos, imprimir el valor de la variable numérica alterada solamente si ha cambiado a ser un numero multiplo de 9. 
- Utilice, a manera de ejemplo, el ejercicio hecho en clase.
