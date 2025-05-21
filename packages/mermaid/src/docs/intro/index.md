graph TD
    A[Junta Directiva del Hospital] --> B(Gerencia General)

    B --> C{Representante de la Dirección para el SGC}
    B --> D(Dirección Médica)
    B --> E(Dirección Administrativa y Financiera)
    B --> F(Dirección de Enfermería)
    B --> G(Dirección de Calidad y Seguridad del Paciente)

    C --> C1(Equipo de Gestión de Calidad)

    D --> D1(Jefes de Servicios Médicos)
    D1 --> D1a(Médicos Especialistas)
    D1 --> D1b(Médicos Generales)

    E --> E1(Departamento de Recursos Humanos)
    E --> E2(Departamento de Adquisiciones y Logística)
    E --> E3(Departamento de Mantenimiento e Infraestructura)
    E --> E4(Departamento de Tecnología de la Información)

    F --> F1(Jefes de Áreas de Enfermería)
    F1 --> F1a(Enfermeras Jefes de Sala)
    F1 --> F1b(Enfermeras Profesionales)
    F1 --> F1c(Auxiliares de Enfermería)

    G --> G1(Auditoría Interna de Calidad)
    G --> G2(Gestión de Riesgos)
    G --> G3(Gestión Documental y Control de Registros)
    G --> G4(Gestión de No Conformidades y Acciones Correctivas)
    G --> G5(Educación y Capacitación en Calidad)

    style A fill:#FFC107,stroke:#333,stroke-width:2px
    style B fill:#8BC34A,stroke:#333,stroke-width:2px
    style C fill:#2196F3,stroke:#333,stroke-width:2px
    style G fill:#FF5722,stroke:#333,stroke-width:2px
