1. ¿Por qué es importante encapsular los atributos como privados?
Encapsular los atributos como privados es fundamental para proteger los datos internos del objeto.
De esta manera, se evita que otras clases modifiquen directamente el estado del objeto sin control, lo que podría causar errores o comportamientos inesperados.
Al usar métodos get y set, el acceso y modificación de los atributos se realiza de forma controlada, permitiendo aplicar validaciones y mantener la coherencia del objeto.

3. ¿Qué ventaja tiene usar constructores sobrecargados en esta clase?
Usar constructores sobrecargados permite crear objetos de la clase CuentaBancaria de diferentes formas según la necesidad.
Por ejemplo, el constructor por defecto asigna valores preestablecidos, útil cuando no se tiene información inicial.
En cambio, el constructor con parámetros permite inicializar la cuenta con datos personalizados.
Esta flexibilidad mejora la reutilización del código y facilita la creación de objetos con distintos contextos.

5. ¿Cómo aseguran los setters la integridad de los datos?
Los métodos set (setters) aseguran la integridad de los datos al permitir establecer nuevos valores solo si cumplen ciertas condiciones.
 Por ejemplo, el método setSaldo() evita asignar valores negativos, y setTitular() verifica que el nombre no esté vacío ni sea nulo.
Estas validaciones previenen errores lógicos y garantizan que los atributos del objeto siempre tengan valores válidos y coherentes.
