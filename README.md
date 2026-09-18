# ahorro-agua-diagrama-flujo
Repositorio público con un diagrama de flujo sobre el ahorro de agua.

## Diagrama de flujo

```mermaid
flowchart TD
    A[Inicio: detectar consumo excesivo de agua] --> B{¿Hay fugas o desperdicios visibles?}
    B -- Sí --> C[Revisar tuberías, grifos y sanitarios]
    C --> D[Corregir fugas y cambiar piezas defectuosas]
    D --> E[Medir consumo semanal]
    B -- No --> E
    E --> F{¿El consumo sigue siendo alto?}
    F -- Sí --> G[Aplicar hábitos de ahorro]
    G --> G1[Cerrar grifos mientras te cepillas]
    G --> G2[Usar duchas cortas]
    G --> G3[Reutilizar agua de lavado para limpieza]
    G --> G4[Regar plantas en horas de menor calor]
    G --> G5[Usar electrodomésticos eficientes]
    G --> H[Capacitar a la familia o comunidad]
    H --> I[Monitorear el consumo mensual]
    I --> J{¿Se redujo el consumo?}
    J -- Sí --> K[Continuar con buenas prácticas]
    J -- No --> L[Buscar nuevas mejoras y evaluar hábitos]
    L --> G
    F -- No --> M[Seguimiento continuo del ahorro]
    M --> N[Fin]
    K --> N

    classDef start fill:#d9f2d9,stroke:#2e7d32,stroke-width:2px;
    classDef decision fill:#fff3cd,stroke:#b8860b,stroke-width:2px;
    classDef action fill:#dbeafe,stroke:#1d4ed8,stroke-width:2px;
    classDef end fill:#f8d7da,stroke:#b91c1c,stroke-width:2px;

    class A start;
    class B,F,J decision;
    class C,D,E,G,G1,G2,G3,G4,G5,H,I,L,M action;`classDef nodoFinal fill:#f8d7da...`).
```

## Descripción del proceso

1. Se inicia revisando si existe un consumo excesivo de agua o desperdicio visible.
2. Si hay fugas o mal funcionamiento, se corrigen de inmediato.
3. Luego se evalúa si el consumo sigue siendo alto.
4. En caso afirmativo, se aplican medidas de ahorro como:
   - cerrar grifos al cepillarse
   - tomar duchas cortas
   - reutilizar agua de lavado
   - regar en horarios adecuados
   - usar aparatos eficientes
5. Se capacita a la familia o comunidad sobre hábitos responsables.
6. Se monitorea el consumo mensual para confirmar la reducción.
7. Si no mejora, se repite el proceso y se buscan nuevas estrategias.

## Objetivo

Reducir el consumo de agua, evitar desperdicios y fomentar una cultura responsable del uso del recurso hídrico.

## Licencia

Este proyecto se comparte con fines educativos.
