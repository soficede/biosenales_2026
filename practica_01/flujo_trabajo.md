# Flujo de trabajo colaborativo — Git/GitHub

```
 ┌────────────┐     git clone      ┌────────────────┐
 │  GitHub     │ ─────────────────▶│  Repo local     │
 │ (remoto)    │                    │  (mi PC)        │
 └────────────┘                    └────────────────┘
        ▲                                   │
        │                                   │ 1. git pull
        │                                   │    (traer cambios antes de empezar)
        │                                   ▼
        │                          ┌────────────────┐
        │                          │ Editar archivos │
        │                          │ (notebook/script)│
        │                          └────────────────┘
        │                                   │
        │                                   │ 2. git add .
        │                                   ▼
        │                          ┌────────────────┐
        │                          │ git commit -m   │
        │                          │  "mensaje claro"│
        │                          └────────────────┘
        │                                   │
        │              3. git push          │
        └───────────────────────────────────┘
```

**Pasos del flujo:**
1. `git pull` — traer los últimos cambios del repositorio antes de empezar a trabajar.
2. Editar los archivos de la práctica dentro de la carpeta correspondiente (ej. `practica_1`).
3. `git add .` — registrar los cambios localmente.
4. `git commit -m "mensaje descriptivo"` — guardar con mensaje claro.
5. `git push` — subir los cambios al repositorio en GitHub.
