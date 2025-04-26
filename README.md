# diagrama_trigliceridos.md
## Diagrama de Flujo de los Triglicéridos

```mermaid
graph TD
    A[Inicio: Triacilgliceroles (Triglicéridos)] --> B(Base Química: Glicerol + 3 Ácidos Grasos (enlaces éster));
    B --> C{¿Ácidos Grasos Iguales?};
    C -- Sí --> D[Triacilglicerol Simple];
    C -- No --> E[Triacilglicerol Mixto];
    B --> F(Naturaleza Apolar e Hidrofóbica);
    A --> G(Función Principal: Almacenamiento de Energía a Largo Plazo);
    G --> H{¿Necesidad de Energía?};
    H -- Sí --> I(Hidrólisis por Lipasas);
    I --> J(Liberación de Glicerol y Ácidos Grasos);
    J --> K(Metabolismo para Obtener Energía);
    H -- No --> L(Almacenamiento en Adipocitos/Semillas);
    A --> M(Otras Funciones);
    M --> N[Aislamiento Térmico (Animales)];
    M --> O[Protección de Órganos];
    M --> P[Flotabilidad (Animales Acuáticos)];
    M --> Q[Fuente de Ácidos Grasos Esenciales];
    A --> R(Aplicaciones);
    R --> S[Fuente de Energía Dietética];
    R --> T[Industria Alimentaria];
    R --> U[Producción de Biocombustibles];
    R --> V[Aislamiento/Lubricación Industrial];
    A --> W(Datos Relevantes);
    W --> X[Almacenamiento Eficiente];
    W --> Y[Metabolismo Regulado];
    W --> Z[Concentración en Sangre y Salud];
    W --> AA[Diferencia entre Grasas y Aceites];
    A --> BB(Aspectos Estructurales);
    BB --> CC[Esqueleto de Glicerol];
    BB --> DD[Enlaces Éster];
    BB --> EE[Variedad de Cadenas de Ácidos Grasos];
    BB --> FF[Configuración Espacial];
    FF --> GG[Influencia en Propiedades Físicas];
    GG --> HH[Fin];
