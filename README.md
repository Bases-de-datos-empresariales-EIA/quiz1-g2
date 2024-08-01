# Gestión de Alquiler de Vehículos

## Contexto del Negocio

Una compañía dedicada a la renta de vehículos requiere un sistema para manejar sus vehículos, clientes, contratos de alquiler, y los empleados que gestionan cada contrato. El objetivo es mantener un registro actualizado de los vehículos disponibles, los clientes, y los detalles de cada contrato de alquiler.

## Descripción de los Elementos del Negocio

1. **Vehículo**:
   - **Descripción**: Los vehículos disponibles para alquiler.
   - **Atributos Clave**: Matrícula del vehículo, modelo, año.

2. **Cliente**:
   - **Descripción**: Las personas que alquilan vehículos.
   - **Atributos Clave**: ID del cliente, nombre del cliente, correo electrónico.

3. **Contrato de Alquiler**:
   - **Descripción**: Los acuerdos establecidos entre la empresa y el cliente para el alquiler de vehículos.
   - **Atributos Clave**: Número de contrato, fecha de inicio, fecha de fin, vehículo alquilado, cliente.

4. **Empleado**:
   - **Descripción**: Los empleados que gestionan los contratos de alquiler.
   - **Atributos Clave**: ID del empleado, nombre del empleado, contratos gestionados.

5. **Reserva**:
   - **Descripción**: Las reservaciones hechas por los clientes antes de la formalización del contrato.
   - **Atributos Clave**: ID de reserva, fecha de reserva, cliente asociado, vehículo reservado.

## Instrucciones
- Construya en Figma o a mano el diagrama Entidad-Relación del negocio descrito anteriormente siguiendo el estándar explicado en clase (70%).
- Justifique la elección de cada tipo de relación (one-to-one, one-to-many, many-to-many) (10%).
- Justifique por qué cada tabla es transaccional o maestra (20%).
- Recuerde el estándar de construcción del diagrama E-R:
    - Entidades: PascalCase.
    - Campos: camelCase.
    - Cada relación `one` debe ser denotada en la fuente con un singular. Además, debe llevar un círculo en el destino.
    - Cada relación `many` debe ser denotada en la fuente con un plural. Además, debe llevar un triángulo en el destino.
    - Cada entidad maestra es de color verde. Si el diagrama es dibujado a mano, el estudiante debe especificar que la entidad es de tipo maestra.
    - Cada entidad transaccional es de color púrpura. Si el diagrama es dibujado a mano, el estudiante debe especificar que la entidad es de tipo transaccional.

# Entrega
Enviar el diagrama Entidad-Relación y las justificaciones a `daniel.saldarriaga@eia.edu.co`.
