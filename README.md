# 🥋 Dojo Git Jidoka: ¡Proyecto del Caos al Orden! 🚀

---

¡Hola, equipo de Jidoka!

¿Listos para convertir el caos del código en pura armonía y pan comido con Git y GitHub? Hoy, cada uno de ustedes con esfuerzo se convertira en  **"Sensei del Control de Versiones"** y ayudará a escribir HISTORIA para nuestro dojo.

---

## 📖 La Historia más Extraña del Mundo

Tenemos una historia... un poco rara. Un personaje muy particular está haciendo algo ¡igualmente particular! Tu misión es darle vida a esta historia, ¡poniéndole tu propio toque Jidoka!

---

## 🎯 Tu Misión (Kata Jidoka)

1.  **Consigue la historia:** Clona este proyecto a tu compu.
2.  **Crea tu propia rama:** ¡Tu propio espacio secreto para trabajar!
3.  **Edita `historia.md`:** Cambia el personaje y su acción super-rara.
4.  **Sube tu rama:** Manda tu versión a GitHub.
5.  **Crea un Pull Request (PR):** Pide que tu cambio se una a la historia oficial.

---

### **¡Manos a la Obra! (Comandos que te Salvarán)**

#### **Paso 1: ¡Agarra la Historia! (Clonar)**

Abre tu terminal y escribe:

```bash
git clone https://github.com/danielcardenasparra/Dojo-Git-Jidoka-Colaboracion.git
# (este es el repo creado por el Sensei)
```



#### **Paso 2: ¡Crea tu Espacio Personal! (Rama)**
¡Crea tu propia pista de trabajo para no pisar a nadie!


```bash
git checkout -b feature/tu-nombre
# (Ej: feature/ninja-git o feature/el-maestro-del-mal)
```

#### **Paso 3: ¡Dale Rienda Suelta a la Imaginación en historia.md!**
Abre el archivo historia.md . Verás esto:

```markdown

En un rincón olvidado del universo, donde los bytes bailan salsa, nuestro enigmático personaje **[PERSONAJE_MISTERIOSO]** estaba **[ACCION_ABSURDA]** mientras buscaba el sentido de la vida... o al menos, la última versión del café.

```

---

## 🎯 Tu tarea es:

1.  **Reemplaza:** [PERSONAJE_MISTERIOSO] por el nombre más disparatado que se te ocurra (ej. "El Llama-Cebollas", "La Ardilla Espacial", "Don Comillas Locas").
2.  **Reemplaza:** [ACCION_ABSURDA] por algo totalmente ridículo que esté haciendo (ej. "ordenando calcetines con la mente", "dando serenatas a una tostadora", "calculando la velocidad de la luz con un tenedor").
3.  **¡Guarda los cambios! ¡No te olvides de guardar!**

---






#### **Paso 4: ¡Sube tus Cambios! (Add, Commit, Push)**


```bash
# ¿Qué cambiaste?
git status

# ¡Listo para la foto!
git add historia.md

# ¡Toma la foto y ponle un título divertido!
git commit -m "feat: [Tu Personaje] haciendo [Su Acción Absurda]"

# ¡Manda tu rama a la nube!
git push -u origin HEAD

```

#### **Paso 5: ¡Propón tu Obra Maestra! (Pull Request / PR)**

Ahora, pide que tu genialidad se una a la historia principal.

1.  Ve al repositorio del Dojo en tu navegador de GitHub.
2.  Verás una notificación amarilla con tu rama. Haz clic en el botón verde **"Compare & pull request"**.
    * *Si no la ves, ve a la pestaña **"Pull requests"** y haz clic en **"New pull request"**.*
3.  Asegúrate de que la flecha apunte desde tu rama (`feature/tu-nombre`) hacia la rama `main`.
4.  Escribe un título creativo para tu PR (ej. `feat: La llegada de 'El Llama-Cebollas'`).
5.  En la descripción, explica brevemente tu aporte.
6.  Finalmente, haz clic en el botón verde **"Create pull request"**.

---

### ✨ ¡La Fusión Mágica!

¡Listo! Tu Pull Request ha sido enviado y ahora está esperando la aprobación del Sensei del Dojo. Yo (Sensei) revisaré las maravillosas creaciones del equipo y las fusionaré (merge) a la historia oficial.

---

### 🔄 ¡Actualiza tu Copia Local!

Una vez que tu PR (o el de tus compañeros) sea fusionado, tu copia local de la historia estará desactualizada. Para obtener la versión final con todas las locuras, sigue estos pasos en tu terminal:


```bash
# Trae toda la información (ramas, commits, etc.) del repositorio remoto
git fetch --all

# Muestra todas las ramas locales y remotas
git branch -a

# Cambia a la rama de un compañero para ver su trabajo
git checkout feature/(ninja-git)
```
¡Así tendrás la historia más completa y extraña del mundo en tu computador!

¡Que el flujo de Git te acompañe!
