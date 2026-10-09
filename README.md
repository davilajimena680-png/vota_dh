# vota_dh
# Vota Dolores Hidalgo (vota_dh)

Aplicacion desarrollada en Flutter aplicando TDD (Test-Driven Development) para un plebiscito vecinal digital.

---

## Evidencia de Pruebas (TDD - Desarrollo Guiado por Pruebas)

A continuacion se muestra el proceso paso a paso de cada ronda, evidenciando el ciclo de Rojo (Prueba fallida) y Verde (Prueba superada), culminando con la ejecucion general y la integracion completa.

### 1. Resumen General de Pruebas
![Todas las pruebas en verde](imagenes/terminal_todas_las_pruebas_en_verde.png)

---

### 2. Ciclo de Rondas (Rojo y Verde)

#### Ronda 1: Voto Valido
* Rojo (Error inicial):
  ![Ronda 1 Rojo](imagenes/ronda_1_rojo_voto_valido.png)
* Verde (Prueba superada):
  ![Ronda 1 Verde](imagenes/ronda_1_verde_voto_valido.png)

#### Ronda 2: Opcion Invalida
* Rojo (Null Check / Fallo):
  ![Ronda 2 Rojo Fallo](imagenes/ronda_2_rojo_opcion_invalida_fallo.png)
* Verde (Prueba superada):
  ![Ronda 2 Verde](imagenes/ronda_2_verde_opcion_invalida.png)

#### Ronda 3: Usuario Repetido
* Rojo (Fallo por duplicidad):
  ![Ronda 3 Rojo](imagenes/ronda_3_rojo_usuario_repetido.png)
* Verde (Prueba superada):
  ![Ronda 3 Verde](imagenes/ronda_3_verde_usuario_repetido.png)

#### Ronda 4: Calculo de Porcentajes
* Verde (Prueba superada):
  ![Ronda 4 Verde](imagenes/ronda_4_verde_porcentajes.png)

#### Ronda 5: Determinar Ganador
* Rojo (Metodo faltante):
  ![Ronda 5 Rojo](imagenes/ronda_5_rojo_determinar_ganador.png)
* Verde (Prueba superada):
  ![Ronda 5 Verde](imagenes/ronda_5_verde_determinar_ganador.png)

#### Ronda 6 y 7: Empates y Votacion Cerrada
* Empates (Verde):
  ![Ronda 6 Verde](imagenes/ronda_6_verde_empate.png)
* Votacion Cerrada (Rojo):
  ![Ronda 7 Rojo](imagenes/ronda_7_rojo_votacion_cerrada.png)
* Votacion Cerrada (Verde):
  ![Ronda 7 Verde](imagenes/ronda_7_verde_votacion_cerrada.png)

---

### 3. Prueba de Integracion Completa
![Simulacion Completa](imagenes/prueba_integracion_completa.png)
