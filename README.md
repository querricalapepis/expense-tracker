# 💵 Expense Tracker 💵

En este ejercicio teneis que crear una app que lleve cuentas de cuanto dinero se deben un grupo de personas entre si.

## Premisa

Si vas con un grupo de amigos al McDonalds y pagas tú, es muy facil hacer cuentas: todos te tienen que pagar a ti el precio de lo que se han pedido.

Pero si vais a varios sitios y cada vez paga alguien, es dificil calcular cuanto le debes a cada persona. Podemos hacer una app donde cada vez que paguemos algo, apuntemos cuanto le debe cada uno al resto. La app calculará el total de la deuda de cada persona e indicara a quienes tienen que pagar.

## Requerimientos

1. Añadir compras: formulario donde se indique el nombre de la compra, quienes han pagado, cuanto debe cada persona, etc.
2. Lista con todos los gastos.
3. Resumen que indique la deuda total de cada persona a partir de todas las compras.

## Aspectos importantes

- Lo más importante es aprender a hacer formularios de mucha calidad: controlar que la entrada sea valida, aprender como se accede a los valores de los campos, como hacer submit, etc. Hay que investigar la manera que React recomienda para hacerlos.
- Otro aspecto importante es organizar bien los datos que almacena la aplicación: ¿Que componentes o contextos son responsable de almacenar la información? ¿Que componentes son puramente visuales y no necesitan acceso a la info? Os recomiendo este [video](https://www.youtube.com/watch?v=zpUMRsAO6-Y&list=WL&index=1&ab_channel=freeCodeCampTalks) si no sabeis por donde empezar.
- El CSS da absolutamente igual, solo usadlo para temas estructurales y que sea legible.

> Si lo veis útil en vuestro aprendizaje, podeis implementar guardar la info en un JSON + usar [localStorage](https://es.javascript.info/localstorage) para poder mantener la info incluso si se refresca la pestaña.
