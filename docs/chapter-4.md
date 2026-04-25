## 4.1 Style Guidelines

### 4.1.1 General Style Guidelines

### 4.1.2 Web Style Guidelines

## 4.2 Information Architecture

### 4.2.1 Organization Systems

### 4.2.2 Labeling Systems

### 4.2.3 SEO Tags and Meta Tags

### 4.2.4 Searching Systems

### 4.2.5 Navigation Systems

## 4.3 Landing Page UI Design

### 4.3.1 Landing Page Wireframe

### 4.3.2 Landing Page Mock-up

## 4.4 Web Applications UX/UI Design

### 4.4.1 Web Applications Wireframes

### 4.4.2 Web Applications Wireflow Diagrams

### 4.4.3 Web Applications Mock-ups

### 4.4.4 Web Applications User Flow Diagrams

## 4.5 Web Applications Prototyping

## 4.6 Domain-Driven Software Architecture

### 4.6.1 Software Architecture Context Diagram

El sistema tiene como actor principal al **dueño del restaurante**, quien accede desde una interfaz web Angular.

<img width="267" height="620" alt="contexto" src="https://github.com/user-attachments/assets/67481017-f88b-4c69-b8d5-e9dac63b09fe" />

### 4.6.2 Software Architecture Container Diagrams.

### 4.6.3 Software Architecture Components Diagrams.

## 4.7 Software Object-Oriented Design

### 4.7.1 Class Diagrams


<img alt="Untitled diagram-2025-10-09-034906" src="https://github.com/user-attachments/assets/7cd76b45-2db5-4829-947f-626c5e9c8989" />


<img alt="1" src="https://github.com/user-attachments/assets/215ac1e6-a2cf-402c-860a-5bc39099118a" />

<img alt="2" src="https://github.com/user-attachments/assets/7de7aabb-a9af-430c-8132-bd98b56e7e32" />

<img alt="3" src="https://github.com/user-attachments/assets/375c8a3e-7681-464c-b13c-a81289038fe0" />

<img alt="4" src="https://github.com/user-attachments/assets/7b090aca-b29f-4046-b750-085e7ca219ab" />

<img alt="5" src="https://github.com/user-attachments/assets/050f0fe3-540b-4dd1-ac65-31cc6efa786f" />

<div style="page-break-after: always;"></div>

### 4.7.2 Class Dictionary

## Suscripción

| Clase                      | Tipo             | Descripción                                               | Propósito                                                                                                                                      |
|----------------------------|------------------|-----------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| **SubscriptionController** | Controlador      | Maneja las peticiones HTTP relacionadas con suscripciones | Expone endpoints REST para que los usuarios puedan ver planes, suscribirse, consultar su suscripción y cancelarla                              |
| **SubscriptionService**    | Servicio         | Contiene la lógica de negocio de las suscripciones        | Orquesta el proceso completo: valida datos, procesa pagos, activa suscripciones y gestiona renovaciones                                        |
| **Subscription**           | Entidad          | Representa una suscripción activa de un usuario           | Almacena información de la suscripción individual: qué usuario, qué plan eligió, cuándo inicia/termina, estado del pago                        |
| **SubscriptionPlan**       | Entidad/Catálogo | Representa los planes de suscripción disponibles          | Define los diferentes planes que se ofrecen (Básico, Premium, Enterprise) con sus precios, características y límites                           |
| **SubscriptionRepository** | Repositorio      | Acceso a datos de suscripciones de usuarios               | Maneja operaciones CRUD de las **suscripciones activas/históricas de usuarios**. Cada vez que un usuario se suscribe, se crea un registro aquí |
| **PlanRepository**         | Repositorio      | Acceso a datos de planes disponibles                      | Maneja operaciones CRUD de los **planes que ofreces como negocio** (catálogo de productos). Son los planes base que no cambian por usuario     |
| **SubscriptionStatus**     | Enum             | Estados posibles de una suscripción                       | Rastrea el flujo: desde que el usuario selecciona un plan, valida pago, procesa, hasta que queda activa o falla                                |
| **BillingPeriod**          | Enum             | Períodos de facturación                                   | Define si el plan se cobra mensual, trimestral o anualmente                                                                                    |
| **PaymentClient**          | Cliente          | Interfaz para procesar pagos                              | Se comunica con una pasarela de pago externa (Stripe, PayPal, etc.) para procesar transacciones                                                |
| **PaymentData**            | DTO              | Datos de pago del usuario                                 | Encapsula información sensible: tarjeta, titular, fecha de expiración, CVV                                                                     |
| **PaymentResult**          | DTO              | Resultado del procesamiento de pago                       | Contiene si el pago fue exitoso, ID de transacción y mensajes de error si aplica                                                               |

---

## Inventario

| Clase                   | Tipo        | Descripción                                      | Propósito                                                                                            |
|-------------------------|-------------|--------------------------------------------------|------------------------------------------------------------------------------------------------------|
| **InventoryController** | Controlador | Maneja peticiones HTTP de inventario             | Expone endpoints para registrar productos, actualizar stock y consultar inventario                   |
| **InventoryService**    | Servicio    | Lógica de negocio del inventario                 | Gestiona operaciones de productos: crear, actualizar stock, descontar ingredientes usados en órdenes |
| **Product**             | Entidad     | Representa un producto/ingrediente en inventario | Almacena información del producto: nombre, categoría, precio de compra, stock actual, proveedor      |
| **ProductStatus**       | Enum        | Estados del producto                             | Indica el estado del producto en el sistema: pendiente, registrado, stock disponible, bajo o agotado |
| **ProductRepository**   | Repositorio | Acceso a datos de productos                      | Maneja operaciones CRUD de productos en inventario                                                   |

---

## Menú

| Clase              | Tipo        | Descripción                     | Propósito                                                                       |
|--------------------|-------------|---------------------------------|---------------------------------------------------------------------------------|
| **MenuController** | Controlador | Maneja peticiones HTTP del menú | Expone endpoints para crear platos y consultar el menú                          |
| **MenuService**    | Servicio    | Lógica de negocio del menú      | Gestiona la creación y consulta de platos disponibles para venta                |
| **Dish**           | Entidad     | Representa un plato del menú    | Almacena información del plato: nombre, descripción, precio de venta, categoría |
| **DishStatus**     | Enum        | Estados del plato               | Indica si el plato está en proceso de creación o ya está registrado en el menú  |
| **DishRepository** | Repositorio | Acceso a datos de platos        | Maneja operaciones CRUD de platos del menú                                      |

---

## Órdenes

| Clase                | Tipo                   | Descripción                              | Propósito                                                                                       |
|----------------------|------------------------|------------------------------------------|-------------------------------------------------------------------------------------------------|
| **OrderController**  | Controlador            | Maneja peticiones HTTP de órdenes        | Expone endpoints para cargar órdenes, consultarlas y filtrar por rango de fechas                |
| **OrderService**     | Servicio               | Lógica de negocio de órdenes             | Procesa órdenes de venta, calcula totales, actualiza inventario y coordina con otros servicios  |
| **Order**            | Entidad                | Representa una orden de venta            | Almacena información de la orden: número, items vendidos, total, fecha, estado de procesamiento |
| **OrderItem**        | Entidad                | Representa un ítem dentro de una orden   | Detalle de cada plato vendido: qué plato, cantidad, precio unitario, subtotal                   |
| **OrderStatus**      | Enum                   | Estados de la orden                      | Rastrea el procesamiento: cargada, procesando, actualizando stock, registrada, completada       |
| **OrderRepository**  | Repositorio            | Acceso a datos de órdenes                | Maneja operaciones CRUD de órdenes, con filtros por fecha y estado                              |
| **MessagingService** | Servicio de mensajería | Publica eventos entre microservicios     | Comunica eventos importantes: orden procesada, actualización de stock, suscripción activada     |
| **StockUpdateEvent** | Evento                 | Evento de actualización de inventario    | Mensaje que se envía cuando una orden requiere descontar stock                                  |
| **InventoryClient**  | Cliente                | Interfaz para comunicarse con Inventario | Permite al servicio de órdenes consultar y actualizar el inventario de otros microservicios     |

<div style="page-break-after: always;"></div>


## 4.8 Database Design

### 4.10.1 Relational Database Diagram

La base de datos **Postgres** mantiene las entidades descritas en los capítulos anteriores:

![WhatsApp Image 2025-11-30 at 9 21 40 PM](https://github.com/user-attachments/assets/59d10088-aa49-4da6-a5b4-be8bac062fe1)

<div style="page-break-after: always;"></div>

## Entidades del Sistema

### 1. USER (Usuario)
Almacena la información de los usuarios del sistema.

| Campo      | Tipo        | Descripción                                       |
|------------|-------------|---------------------------------------------------|
| id         | string (PK) | Identificador único del usuario                   |
| email      | string (UK) | Correo electrónico único del usuario              |
| name       | string      | Nombre completo del usuario                       |
| role       | string      | Rol del usuario en el sistema (admin, user, etc.) |
| created_at | datetime    | Fecha de creación del registro                    |
| updated_at | datetime    | Fecha de última actualización                     |

**Propósito**: Gestionar los usuarios que interactúan con el sistema y pueden adquirir suscripciones.

---

### 2. SUBSCRIPTION (Suscripción)
Registra las suscripciones activas e históricas de los usuarios.

| Campo          | Tipo        | Descripción                                                  |
|----------------|-------------|--------------------------------------------------------------|
| id             | string (PK) | Identificador único de la suscripción                        |
| user_id        | string (FK) | Referencia al usuario suscrito                               |
| plan_id        | string (FK) | Referencia al plan seleccionado                              |
| status         | string      | Estado de la suscripción (ACTIVO, EXPIRADO, CANCELADO, etc.) |
| start_date     | datetime    | Fecha de inicio de la suscripción                            |
| end_date       | datetime    | Fecha de finalización de la suscripción                      |
| auto_renew     | boolean     | Indica si la suscripción se renueva automáticamente          |
| payment_method | string      | Método de pago utilizado                                     |
| transaction_id | string      | ID de la transacción de pago                                 |
| created_at     | datetime    | Fecha de creación del registro                               |
| updated_at     | datetime    | Fecha de última actualización                                |

**Propósito**: Controlar el acceso de los usuarios a las funcionalidades del sistema según su plan activo.

---

### 3. SUBSCRIPTION_PLAN (Plan de Suscripción)
Define los diferentes planes de suscripción disponibles.

| Campo          | Tipo        | Descripción                                         |
|----------------|-------------|-----------------------------------------------------|
| id             | string (PK) | Identificador único del plan                        |
| name           | string      | Nombre del plan (Básico, Premium, Enterprise, etc.) |
| description    | string      | Descripción detallada del plan                      |
| price          | decimal     | Precio del plan                                     |
| billing_period | string      | Periodo de facturación (MENSUAL, TRIMESTRAL, ANUAL) |
| features       | string      | Lista de características incluidas (JSON o texto)   |
| max_users      | int         | Número máximo de usuarios permitidos                |
| max_orders     | int         | Número máximo de órdenes permitidas                 |
| created_at     | datetime    | Fecha de creación del registro                      |
| updated_at     | datetime    | Fecha de última actualización                       |

**Propósito**: Definir las opciones de suscripción disponibles con sus características y limitaciones.

---

### 4. PAYMENT_TRANSACTION (Transacción de Pago)
Registra todas las transacciones de pago relacionadas con suscripciones.

| Campo           | Tipo        | Descripción                                            |
|-----------------|-------------|--------------------------------------------------------|
| id              | string (PK) | Identificador único de la transacción                  |
| subscription_id | string (FK) | Referencia a la suscripción asociada                   |
| amount          | decimal     | Monto de la transacción                                |
| currency        | string      | Moneda utilizada (USD, PEN, etc.)                      |
| status          | string      | Estado de la transacción (EXITOSO, FALLIDO, PENDIENTE) |
| transaction_id  | string      | ID único de la transacción del proveedor de pagos      |
| payment_method  | string      | Método de pago usado (tarjeta, PayPal, etc.)           |
| processed_at    | datetime    | Fecha y hora en que se procesó el pago                 |
| created_at      | datetime    | Fecha de creación del registro                         |

**Propósito**: Mantener un historial completo de todas las transacciones de pago para auditoría y seguimiento.

---

### 5. PRODUCT (Producto)
Almacena información de los productos del inventario.

| Campo          | Tipo        | Descripción                                           |
|----------------|-------------|-------------------------------------------------------|
| id             | string (PK) | Identificador único del producto                      |
| name           | string      | Nombre del producto                                   |
| category       | string      | Categoría del producto                                |
| purchase_price | decimal     | Precio de compra del producto                         |
| current_stock  | int         | Stock actual disponible                               |
| unit           | string      | Unidad de medida (kg, unidad, litro, etc.)            |
| purchase_date  | datetime    | Fecha de compra del producto                          |
| supplier       | string      | Proveedor del producto                                |
| status         | string      | Estado del producto (DISPONIBLE, STOCK_BAJO, AGOTADO) |
| created_at     | datetime    | Fecha de creación del registro                        |
| updated_at     | datetime    | Fecha de última actualización                         |

**Propósito**: Gestionar el inventario de productos y materia prima del negocio.

---

### 6. DISH (Platillo)
Contiene los platillos disponibles en el menú.

| Campo       | Tipo        | Descripción                                               |
|-------------|-------------|-----------------------------------------------------------|
| id          | string (PK) | Identificador único del platillo                          |
| name        | string      | Nombre del platillo                                       |
| description | string      | Descripción del platillo                                  |
| price       | decimal     | Precio de venta del platillo                              |
| category    | string      | Categoría del platillo (entrada, principal, postre, etc.) |
| status      | string      | Estado del platillo (DISPONIBLE, NO_DISPONIBLE)           |
| created_at  | datetime    | Fecha de creación del registro                            |
| updated_at  | datetime    | Fecha de última actualización                             |

**Propósito**: Administrar el menú de platillos ofrecidos a los clientes.

---

### 7. ORDER (Orden)
Registra las órdenes realizadas por los clientes.

| Campo        | Tipo        | Descripción                                          |
|--------------|-------------|------------------------------------------------------|
| id           | string (PK) | Identificador único de la orden                      |
| order_number | string (UK) | Número único de orden para identificación            |
| total_amount | decimal     | Monto total de la orden                              |
| status       | string      | Estado de la orden (CARGADA, PROCESANDO, COMPLETADA) |
| order_date   | datetime    | Fecha y hora en que se realizó la orden              |
| processed_at | datetime    | Fecha y hora en que se procesó la orden              |
| created_at   | datetime    | Fecha de creación del registro                       |
| updated_at   | datetime    | Fecha de última actualización                        |

**Propósito**: Gestionar las órdenes de los clientes y su procesamiento.

---

### 8. ORDER_ITEM (Item de Orden)
Detalla los platillos incluidos en cada orden.

| Campo      | Tipo        | Descripción                           |
|------------|-------------|---------------------------------------|
| id         | string (PK) | Identificador único del item          |
| order_id   | string (FK) | Referencia a la orden principal       |
| dish_id    | string (FK) | Referencia al platillo ordenado       |
| dish_name  | string      | Nombre del platillo (desnormalizado)  |
| quantity   | int         | Cantidad de platillos ordenados       |
| unit_price | decimal     | Precio unitario del platillo          |
| subtotal   | decimal     | Subtotal del item (cantidad × precio) |
| created_at | datetime    | Fecha de creación del registro        |

**Propósito**: Detallar el contenido específico de cada orden.

---

### 9. INCOME_DETAIL (Detalle de Ingresos)
Desglosa la información detallada de ingresos en un reporte.

| Campo               | Tipo        | Descripción                            |
|---------------------|-------------|----------------------------------------|
| id                  | string (PK) | Identificador único del detalle        |
| report_id           | string (FK) | Referencia al reporte principal        |
| total_sales         | decimal     | Total de ventas en el periodo          |
| order_count         | int         | Cantidad de órdenes procesadas         |
| average_order_value | decimal     | Valor promedio por orden               |
| sales_by_dish       | string      | Ventas desglosadas por platillo (JSON) |
| sales_by_day        | string      | Ventas desglosadas por día (JSON)      |
| created_at          | datetime    | Fecha de creación del registro         |

**Propósito**: Proporcionar análisis detallado de los ingresos generados.

---

### 10. LOSS_DETAIL (Detalle de Pérdidas)
Desglosa la información detallada de pérdidas en un reporte.

| Campo                 | Tipo        | Descripción                              |
|-----------------------|-------------|------------------------------------------|
| id                    | string (PK) | Identificador único del detalle          |
| report_id             | string (FK) | Referencia al reporte principal          |
| total_purchases       | decimal     | Total de compras en el periodo           |
| purchase_count        | int         | Cantidad de compras realizadas           |
| purchases_by_category | string      | Compras desglosadas por categoría (JSON) |
| purchases_by_day      | string      | Compras desglosadas por día (JSON)       |
| created_at            | datetime    | Fecha de creación del registro           |

**Propósito**: Proporcionar análisis detallado de las pérdidas o gastos incurridos.

---

## Relaciones entre Entidades

| Relación                           | Cardinalidad | Descripción                                                                                              |
|------------------------------------|--------------|----------------------------------------------------------------------------------------------------------|
| USER → SUBSCRIPTION                | 1:N          | Un usuario puede tener múltiples suscripciones (historial de suscripciones actuales y pasadas)           |
| SUBSCRIPTION → SUBSCRIPTION_PLAN   | N:1          | Cada suscripción pertenece a un plan específico; un plan puede ser usado por múltiples suscripciones     |
| SUBSCRIPTION → PAYMENT_TRANSACTION | 1:N          | Una suscripción puede generar múltiples transacciones (pagos iniciales, renovaciones, intentos fallidos) |
| ORDER → ORDER_ITEM                 | 1:N          | Una orden contiene múltiples items; cada item pertenece a una única orden                                |
| DISH → ORDER_ITEM                  | 1:N          | Un platillo puede estar en múltiples items de orden; cada item referencia un único platillo              |

---
