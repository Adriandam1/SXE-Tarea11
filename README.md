# SXE-Tarea11

### Enunciado
Tareas a realizar:
- Traspasar los datos proporcionados a una instalación de Odoo.
- La instalación de Odoo debe incluir, como mínimo, los datos incluidos en el archivo `datos.zip`.
- Se debe incluir algún módulo de los propuestos en el archivo de “Odoo Configuración mínima inicial” que se considere de utilidad para el día a día de la empresa e introducir o configurarlo.

---

## Índice  
1. Creación de nuestra nueva base de datos  
2. Instalación de aplicaciones  
3. Configuración de la que será nuestra empresa  
4. Añadir nuestros contactos  
5. Añadir nuestras facturas  
6. Backup de la base de datos final  

---

### 1. Creación de nuestra nueva base de datos  

Lo primero que vamos a hacer, ya que usamos la máquina virtual del ejercicio anterior, es crear una nueva base de datos.  

- Accedemos a la URL **/web/database/manager** desde el navegador para gestionar las bases de datos.  
![sxe1](https://github.com/user-attachments/assets/9170ee0f-a0d5-4960-b515-107933b5cfb8)  

- Rellenamos los datos necesarios para crear la nueva base de datos. Esto incluye el nombre de la base de datos, el correo del administrador y su contraseña.  
![sxe2](https://github.com/user-attachments/assets/1641a9d4-9141-4203-9cc9-2ce14c8e4164)  

- Elegimos la nueva base de datos y nos logeamos con las credenciales que acabamos de configurar.  
![sxe3](https://github.com/user-attachments/assets/d784332c-f9e2-4a95-b480-9a7c5916d1d0)  

---

### 2. Instalación de aplicaciones  

En esta nueva base de datos no tenemos las aplicaciones instaladas, por lo que el primer paso será instalarlas.  

- Buscamos la aplicación de **Ventas** en la lista de aplicaciones. Esta nos permitirá gestionar las facturas y las ventas de nuestros productos o servicios.  
![sxe4](https://github.com/user-attachments/assets/3eb0c660-9f0c-4ca5-8dd0-6764ba787c1b)  

- También instalamos la aplicación de **Contactos** para registrar la información de nuestros clientes y proveedores.  
![sxe5](https://github.com/user-attachments/assets/d8273750-3cd6-4006-9c72-80f3a40476f4)  

---

### 3. Configuración de nuestra empresa  

Realizamos los ajustes necesarios para que la configuración de la empresa sea adecuada a nuestras necesidades.  

- Configuramos la localización fiscal, los valores por defecto y los datos básicos de la empresa. Esto incluye nombre, dirección, moneda, entre otros.  
![sxe6](https://github.com/user-attachments/assets/c8d89098-ba97-4ed7-963f-9163aaf81c5f)  

- Personalizamos el formato de las facturas, adaptándolas al diseño requerido por nuestra empresa.  
![sxe7](https://github.com/user-attachments/assets/58bf98a3-42cc-4d5a-81d1-935b2cd132ed)  

- Verificamos el contacto principal de nuestra empresa, asegurándonos de que los datos son correctos.  
![sxe8](https://github.com/user-attachments/assets/40a19651-92f6-4bd7-9718-ef4464c93b69)  

- Comprobamos el diseño de las facturas para confirmar que todo está configurado correctamente.  
![sxe9](https://github.com/user-attachments/assets/b0b25649-e8ff-4a8a-8cb1-d880a52b3bc2)  

---

### 4. Añadir nuestros contactos  

Para añadir todos los contactos de manera eficiente, importamos los datos desde un archivo Excel.  

- Utilizamos la funcionalidad de importación de contactos para cargar la información de clientes y proveedores desde nuestro archivo de datos.  
![sxe10](https://github.com/user-attachments/assets/f8af15e4-4a9b-4144-9ea0-68ffdfdb8c32)  

- Verificamos que los contactos se han creado correctamente en la base de datos.  
![sxe11](https://github.com/user-attachments/assets/6307ed1b-e065-497c-8d69-32757b7029d1)  

---

### 5. Añadir nuestras facturas  

Ahora procedemos a crear las facturas de nuestros clientes y proveedores.  

- Creamos una factura desde el módulo correspondiente, especificando todos los detalles necesarios (cliente, productos/servicios, precio, etc.).  
![sxe12](https://github.com/user-attachments/assets/261857c3-a73f-4789-b15a-2452a3fa5cba)  

- Registramos el pago asociado a cada factura desde la opción **Registrar Pago**.  
![sxe13](https://github.com/user-attachments/assets/82c8be97-7f6c-483a-a41e-9c357f758c5a)  

- Comprobamos cómo se reflejan las facturas creadas en el sistema.  
![sxe14](https://github.com/user-attachments/assets/27100946-0bbd-451c-98df-4650a5f38022)  

- Para las facturas de los proveedores, seguimos el mismo procedimiento, pero accedemos a la pestaña **Proveedores** dentro del módulo de facturación.  
![sxe15](https://github.com/user-attachments/assets/6bc7e49f-b0bc-443c-8a40-1375316a6a98)  

---

### 6. Backup de la base de datos final  

Finalmente, realizamos un backup de nuestra base de datos para asegurarnos de que todo lo realizado está protegido.  

- Accedemos nuevamente a **/web/database/manager** y seleccionamos la opción **Backup** para descargar una copia de seguridad de nuestra base de datos.  
![sxe16](https://github.com/user-attachments/assets/0b95cf98-a2e7-484c-89c4-c3336eec8eca)  


-------------------------------------------------------
### 7. Edito: Apartado Odoo Configuracion minima inicial. Instalaremos Inventario:
Esta aplicación nos permitira planificar y registrar las entregas y recepciones de pedidos, tanto de nuestras ventas, como de nuestros proveedores.

Lo primero que tenemos es que instalar la aplicación, buscamos "inventario":
![zznuevo1](https://github.com/user-attachments/assets/522eb361-c352-4999-8e16-20bef1058756)

Una vez instalado, ya podemos empezar a trabajar con él. Podemos empezar creando una nueva orden de entrega: 
![zznuevo2](https://github.com/user-attachments/assets/2d9ff42b-b4cd-4239-b66e-32183ee04608)  


Rellenamos los campos como direccion de entrega, fecha, los productos y la demanda y le damos a validar:
![zznuevo3](https://github.com/user-attachments/assets/6adaec5c-00b5-4b14-8789-c41d507bf1f6)

Podemos dejar la orden pendiente, o validarle directamente, si lo hacemos tenemos la opcion de enviar un SMS o mail de confirmación(esto podemos automatizarlo para que no nos lo pida)

Comprobamos que nos aparece el codigo en la parte superior izquierda para confirmar
![zznuevo4](https://github.com/user-attachments/assets/d0c6aed6-d5b9-4200-9447-42a6d8d18c68)

Para las recepciones sería exactamente lo mismo

En *productos* los podemos configurar en la pestaña productos:
![zznuevo5](https://github.com/user-attachments/assets/8c49f3a4-cfbb-4fbc-98f1-cbd90dc3d6f8)

En el apartado  *informe* podemos comprobar el historial de operaciones, análisis de movimientos, ubicaciones, comprobar el stock y modificarlo...
![zznuevo7](https://github.com/user-attachments/assets/8dd6d318-b185-4e3f-aced-3132afbce7bf)

Ejemplo con **cartuchos de tinta**:
![zznuevo8](https://github.com/user-attachments/assets/93cf87b8-2caa-489b-bca4-24031413fc34)


También es muy interesante el apartado *Configuración* podemos configurar un montón de parametros, es interesante el subapartado almacenes, en el que podemos configurar nuestros almacenes:
![zznuevo6](https://github.com/user-attachments/assets/f75e36c5-6a8e-49a7-9b73-6d97b6cb5592)


























