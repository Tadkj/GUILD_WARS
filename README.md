# ⚔️ GUILD WARS | SEASON: BETA TEST (v0.1)

![Status](https://img.shields.io/badge/STATUS-ONLINE-brightgreen) ![Version](https://img.shields.io/badge/VERSION-v0.1_BETA-blue) ![Duration](https://img.shields.io/badge/DURATION-21_DAYS-orange)

> **"Optimización del hardware biológico, incremento de stats y depuración de bloatware."**

## 📖 Sobre el Proyecto

**GUILD WARS** es un framework de gamificación diseñado para grupos de amigos con perfiles técnicos (Ingeniería, IT, Arquitectura) y afinidad por la cultura pop (Gaming/Anime). El objetivo no es simplemente perder peso, sino "refactorizar" el cuerpo humano a través de mecánicas de RPG, competencia financiera y transparencia de datos.

La **Season: Beta Test** es una prueba piloto de 21 días para calibrar la dificultad y el compromiso de los usuarios.

---

## 💰 Economía del Juego (The Contract)

El sistema opera bajo un modelo de incentivos financieros de alto riesgo.

### 💎 The Loot Box (El Bote)
* **Buy-in:** `$[MONTO_A_VOTAR]` USD por jugador (Pago anticipado).
* **Winner Takes All:** El jugador con el `SCORE_FINAL` más alto reclama el 100% del bote acumulado.

### 📉 Sistema de Penalizaciones (Nerfs)
Los jugadores que no cumplan con los estándares de rendimiento sufrirán sanciones económicas que engrosarán el bote del ganador.

1.  **Multa por Regresión:** Si `Peso_Final > Peso_Inicial` (el usuario engordó), paga una multa equivalente al valor del Buy-in.
    * *Nota:* El estancamiento (`Peso_Final == Peso_Inicial`) **no** se penaliza.
2.  **Multa por Last Place (Opcional):** Si se aprueba por votación, el jugador en la última posición del ranking paga multa.

### 🛡️ Cláusula de Protección Financiera (Anti-Double Charge)
> **EXCEPTION HANDLER:** Un jugador no puede ser multado más de una vez por temporada.
>
> `IF (Jugador_Engorda == TRUE) AND (Jugador_Ultimo == TRUE)`
> `THEN (Cobrar_Multa_Una_Vez)`
>
> *Explicación:* Se evita el castigo redundante a un mismo usuario, aunque sí se pueden multar a múltiples usuarios distintos.

---

## 📊 El Algoritmo de Puntuación

El `SCORE_FINAL` se calcula mediante una suma ponderada de tres variables críticas:

| Variable | Peso (%) | Descripción |
| :--- | :---: | :--- |
| **RETO FÍSICO** | **40%** | Porcentaje de mejora personal (*Tú vs. Tú*). Delta entre Día 1 y Día 21. |
| **HÁBITOS (GRINDING)** | **35%** | Consistencia diaria reportada en logs (Telegram). |
| **PESO CORPORAL** | **25%** | Porcentaje de masa perdida en báscula. |

---

## 📸 Registro de Actividad (Daily Logs)

Para farmear puntos de experiencia (XP), los usuarios deben subir evidencia al repositorio central (Grupo de Telegram) antes de las `23:59`.

**Regla de Validación:** *Null evidence = Null points.*

### 1. Quest: #Sudor
Evidencia de actividad cardiovascular o de fuerza.
* *Valid:* Foto en gym, screenshot de Strava/Garmin, Smartwatch stats.

### 2. Quest: #Sano
Evidencia de ingesta de combustible de calidad.
* *Valid:* Foto de comida principal balanceada.
* *Invalid:* Presencia de azúcares refinados, ultraprocesados o alcohol.

---

## 💀 Evento Final: The Gauntlet

Al finalizar el ciclo de 21 días, se convoca una reunión presencial obligatoria para la validación de datos.

### Fase 1: Calibración
Pesaje oficial en la misma báscula para todos los participantes.

### Fase 2: Benchmarks Físicos
Los jugadores deben repetir los ejercicios base grabados el Día 1 para medir su porcentaje de mejora.

#### 🪑 Opción A: Wall Sit (La Silla Invisible)
* **Target:** Resistencia de Cuádriceps / Mental.
* **Ejecución:** Espalda plana contra pared, rodillas a 90º. Brazos cruzados.
* **Métrica:** Tiempo hasta el fallo (segundos).

#### 🦾 Opción B: Iron Waiter (El Camarero de Acero)
* **Target:** Hombros (Deltoides) / Isometría.
* **Ejecución:** Brazos en cruz (T-pose) sosteniendo peso ligero.
* **Métrica:** Tiempo manteniendo la horizontalidad (segundos).

#### 🧗 Opción C: Mountain Climbers (El Escalador)
* **Target:** Cardio / Core.
* **Ejecución:** Plancha alta, rodillas al pecho alternadas dinámicamente.
* **Métrica:** Repeticiones totales en 60 segundos.

---

## ⚙️ Setup & Instalación

Para desplegar este evento en tu grupo de amigos:

1.  **Clonar el Repositorio:** Copiar la [Plantilla de Google Sheets] (enlace a tu hoja).
2.  **Configurar Variables:** Definir fecha de inicio y monto de entrada.
3.  **Invite Users:** Añadir a los participantes al grupo de Telegram y a la Hoja de Cálculo.
4.  **Run:** Iniciar el Día 1 con los videos de referencia para los retos físicos.

---

## 📄 Licencia

Este proyecto es de código abierto para cualquier grupo de amigos que quiera dejar de ser sedentario.
**Copyright © 2026 - El Gremio.**
