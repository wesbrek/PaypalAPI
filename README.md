# PaypalAPI

# ¿Qué es Paypal?
PayPal es una empresa estadounidense que opera en casi todo el mundo un
sistema de pagos en línea que soporta transferencias de dinero entre usuarios y
sirve como una alternativa electrónica a los métodos de pago tradicionales
como cheques y giros postales.

# ¿Para qué sirve Paypal?
PayPal crea formas de administrar y transferir dinero, y ofrece opciones y
flexibilidad al enviar pagos, pagar o recibir pagos.

# Documentación
https://developer.paypal.com/

Aquí se puede encontrar la documentación de PayPal, en esta página se pueden encontrar varios apartados como Revisa, plataforma de comercio de PayPal, suscripciones, pagos, facturación, aceptar pagos con tarjeta.
En revisa se puede encontrar los botones exclusivos de PayPal para el uso comercial. En este apartado se brinda el script para el uso del mismo y le muestra al usuario como utilizarlo.
En plataforma de comercio de PayPal le muestra al usuario los pasos que el maneja mediante el uso de API REST y productos personalizados elaborados por PayPal como son los botones. En este también le brinda algunos beneficios que obtendrá al usar la plataforma de PayPal.
En suscripciones informa que con las suscripciones de PayPal puede generar facturas a los clientes o a servicios. 
Muestra características de integración y los API que este utiliza, también muestra acerca de planes de precios y cómo funciona una integración de suscripciones mediante unos flujos tanto si compra una cuenta de PayPal o sin una cuenta.
En pagos muestra el que se necesita saber para realizar los pagos. De igual manera muestra un flujo en el cual se realiza el pago en PayPal.
En facturación enseña lo que ofrece mediante las facturas, las opciones de integración, el cómo funciona mediante un diagrama y el ciclo de vida de la factura junto con las dos tipos de factura que existe.

# Requisitos
Todas las solicitudes al API de PayPal requieren credenciales para
verificar que el llamado de datos sea hecho a través de una cuenta valida
de PayPal. Los llamados de datos solían requerir estar asociados por
medio de los credenciales a una cuenta de negocios
Todas las funciones del API REST de PayPal están disponibles en una
cuenta “sanbox” gratuita. Para habilitar transacciones con características
en vivo se debe ingresar información adicional y adquirir una cuenta de
negocios.
¿Que necesitas para obtener una cuenta de desarrollador?
Una cuenta ordinaria. PayPal ha dejado de separar la cuenta de sandbox
de su cuenta de desarrollador, por ende, para utilizar los servicios del API
solo necesitas una cuenta en PayPal debidamente verificada.
Con la cuenta ya creada en PayPal te darán un código de credenciales.
Este código de credencial lo puedes utilizar para utilizar los muchos
servicios que PayPal ofrece.

# ¿Cómo usar el API de Paypal?

1. Entrar a este link https://developer.paypal.com/developer/accounts/ <br/>
2. Darle al botón que dice Log in to Dashboard  <br/>
<img src="img/img1.png"> <br/>
3. Se inicia sesión o se crea una nueva cuenta de Paypal. <br/>
<img src="img/img2.png"> <br/>
4. En el menú selecciona la opción que dice Accounts. Ahí podrá ver las cuentas que están asociadas a su cuenta, todas son cuentas de prueba, por defecto Paypal le crea a uno 2 cuentas una de business que una cuenta persona que se usa para hacerse pasar por una empresa y la otra cuenta es para comprar productos la cual ya te tiene dinero y una tarjeta “falsa” que está asociada a la cuenta para hacer pruebas de compra. <br/>
<img src="img/img3.png"> <br/>
5. Al lado de cada cuenta hay un botón que dice Actions el cual hay que darle click y entrará a la configuración de esta cuenta, a esas dos que se crean por defecto hay que darles una contraseña para poder usarlas, luego de ponerle una contraseña a una cuenta esta se activará y podrá ser usada de prueba.<br/> 
6. Luego entre a este link https://www.sandbox.paypal.com/cr/home <br/> 
7. Seleccione el botón de iniciar sesión que se encuentra en la parte de ariba e ingrese con la cuenta que desee, por ejemplo inicie sesión con la cuenta de Business. <br/>
<img src="img/img4.png"> <br/>
8. Aquí podrá ver todo lo que tiene que ver con su cuenta business, entre al menú donde dice Tools y seleccione la opción de All Tools. <br/>
<img src="img/img5.png"> <br/>
