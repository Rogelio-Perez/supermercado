# Proyecto Final de la asignatura de Simulacion Industrial

#### **Universidad:** Benemerita Universidad Autonoma de Puebla
#### **Facultad:** Facultad de Ingenieria
#### **Carrera:** Ingenieria Industrial
#### **Profesor:** Dr. Juvencio Rondal Rivas
#### **Materia:** Simulacion Industrial
#### **Proyecto:** Supermercado
#### **Equipo:** Rogelio Perez Mena, Eugenia Veronica Villa Rivera, Estaban Gadiel Michaca
#### **Semestre:** 7mo
#### **Fecha:** 17 de Noviembre de 2022

# Indice
- <a href="#super">Requerimientos Supermercado</a>
- <a href="#clientes">Requerimientos Clientes</a>
- <a href="#datos-relativos">Datos Relativos</a>

## Objetivo del proyecto
Conocer  el  **número optimo de cajas a instalar** para el **primer año de funcionamiento**.

## Proyecto desarrollado
[**Arena Simulation**](https://rossetti.github.io/RossettiArenaBook/ch2-ArenaEnv.html, "Documentacion de Arena Simulation")
Se desarrollo un modelo de simulacion en Arena Simulation para el supermercado.

## Flujo de trabajo del proyecto
- [x] Definir el objetivo del proyecto
- [x] Definir los datos
- [ ] Definir el flujo del problema
- [ ] Definir los procesos
- [ ] Definir los recursos
- [ ] Definir las reglas
- [ ] Definir las restricciones
- [ ] Definir los resultados
- [ ] Definir los reportes
- [ ] Definir los escenarios
- [ ] Realizar la simulacion
- [ ] Analizar los resultados
- [ ] Concluir

## Diagrama de flujo (Ejemplo)

   ```mermaid
    flowchart LR
    A[Start] --> B{Is it?}
    B -->|Yes| C[OK]
    C --> D[Rethink]
    D --> B
    B ---->|No| E[End]
   ```


## Descripcion del proyecto

<h3 id="super">Supermercado</h3>

El proyecto consiste en **simular** el **funcionamiento** de un **supermercado** durante **un año**. Para ello se **simularan** los **siguientes requerimientos**:
- [ ] **Cajeras contratadas** por un **año como minimo**.
- [ ] **Suelo base** de las cajeras **$15.00 pesos la hora**.
- [ ] **Costo fijo** de mantener una **caja semanalmente**  es  de  **$1,470.00  pesos**.
- [ ] Se debe trabajar **14 horas diarias** *( 8 a.m. a 22 hrs )* .

<h3 id="clientes">Clientes</h3>

Se debe percibir diferentes **tipos de clientes**, con los **siguientes requerimientos**:
- [ ] Clientes de **compra alta**
- [ ] Clientes de **compra media**
- [ ] Clientes de **compra baja**

Los inversionistas saben que <span style="text-decoration:underline; font-weight: bold; color: yellow;" >la compra del cliente es proporcional al  tiempo que este permanece en caja, gastando por cada minuto aproximadamente $50.00 pesos</span>. En la siguiente gráfica se ve la **probabilidad normal** de **permanencia en caja**, por cada **tipo de cliente**.

| Alta | Media | Baja |
| :---: | :---: | :---: |
| (3.5, 1.5) | (2.7, 1.5) | (0.9, 0.3) |

Y las **probabilidades discretas** de que cada uno de los **clientes lleguen al supermercado** son:

| Alta | Media | Baja |
| :---: | :---: | :---: |
| 0.6429 | 0.2143 | 0.1428 |

<h3 id="datos-relativos">Datos relativos</h3>

Otros **datos relativos de la demanda** son los siguientes:

**Frecuencia de llegadas de acuerdo al dia de la semana:**
| Dia | Dist |
| :--- | :--- |
| **Lunes** | NORMAL(2, 0.4) |
| **Martes** | NORMAL(2, 0.4) |
| **Miercoles** | NORMAL(1.7, 0.4) |
| **Jueves** | NORMAL(1.7, 0.4) |
| **Viernes** | NORMAL(0.75, 0.05) |
| **Sabado** | NORMAL(0.75, 0.05) |
| **Domingo** | NORMAL(0.25, 0.05) |

**Frecuencia de llegadas de acuerdo a otros picos del an~o**

| Fecha | Dist |
| :--- | :--- |
| 5 Y 6 DE ENERO (Reyes) | NORMAL(0.16, 0.02) |
| 13 Y 14 DE FEBRERO (DIA DEL AMOR Y LA AMISTAD)  | NORMAL(0.20, 0.03) |
| 30 DE ABRIL (DIA DEL KID) | NORMAL(0.18, 0.02) |
| 9 Y 10 DE MAYO (DIA DE LAS MADRES) | NORMAL(0.22, 0.04) |
| 19 Y 21 DE AGOSTO (COMPRAS ESCOLARES) | NORMAL(0.17, 0.02) |
| 20 AL 24 DE DICIEMBRE (COMPRAS NAVIDEN~AS) | NORMAL(0.17, 0.01) |
| 28 AL 31 DE DICIEMBRE (COMPRAS DE FIN DE AN~O) | NORMAL(0.16, 0.01) |
# supermecado
