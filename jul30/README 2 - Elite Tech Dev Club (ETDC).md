#  README - Elite Tech Dev Club (ETDC)

RENATO RAMIREZ JUL 30 2024

## Checklist for Starting a New Student Organization at Texas Tech University

### Initial Requirements
- [ ] Gather a minimum of five student members including a President and Treasurer.  [**nop*****]()
- [ ] Identify a full-time Texas Tech faculty or staff member to serve as an advisor.

### Registration Process

- [x] Check if the organization's purpose is unique using the Student Org Search Engine on TechConnect.
- [ ] Submit the 'Intent to Form Request' on TechConnect.
- [ ] Schedule and attend a mandatory meeting with the Student Involvement staff.

### Documentation

- [ ] Draft the organization's Constitution and Bylaws.
  - [ ] Define the organization's structure and purpose.
  - [ ] Outline membership requirements and selection processes.
  - [ ] Include officer titles, duties, and election processes.
  - [ ] Establish financial procedures and decision-making processes.
- [ ] Obtain approval for any use of Texas Tech logos through Texas Tech Marketing & Communications.

### Approval and Final Steps

- [ ] Receive confirmation and feedback from the Director of Student Involvement.
- [ ] Complete the Student Org Leader Orientation for new organizations.
- [ ] Submit the New Org Registration including:
  - [ ] Names and contact info for President, Treasurer, and three other members.
  - [ ] Advisor contact information and the signed Advisor Agreement Form.
  - [ ] Uploaded Constitution/Bylaws.
  - [ ] Certificate of completion from SOLO for New Student Orgs.

### Annual Compliance
- [ ] Complete the Student Org Leader Orientation annually.
- [ ] Renew organization registration each school year before the fall classes start.
- [ ] Update organization roster on TechConnect within 10 university working days of any leadership changes.
- [ ] Complete required annual Risk Management Training.

### Resources and Contacts
- [ ] Utilize campus resources during the 30-day grace period to recruit members and organize events.
- [ ] Maintain regular contact with the student organization advisor.

# Índice

1. [Introducción](#introducción)
2. [Compromiso del Proyecto](#compromiso-del-proyecto)
   1. [Tecnologías Utilizadas](##tecnologías-utilizadas)
   2. [Cronograma de Desarrollo](#cronograma-de-desarrollo)

3. [Comunidad de Desarrolladores](#comunidad-de-desarrolladores)
4. [Enfoque en Tecnologías Avanzadas](#enfoque-en-tecnologías-avanzadas)

## Introducción
El "Elite Tech Dev Club" (ETDC) es una organización estudiantil dedicada a dominar y fomentar el uso de tecnologías avanzadas y desafiantes en el desarrollo de software. Nuestro propósito es cultivar una comunidad de programadores expertos que no solo enfrenten retos tecnológicos con entusiasmo sino que también desarrollen soluciones innovadoras para mejorar la experiencia académica.

## Compromiso del Proyecto

EL ETDC planea desarrollar una aplicación de escritorio para Texas Tech University, superior en eficiencia y funcionalidad al sitio web oficial de la universidad.

- ###        Tecnologías Utilizadas

Combinando Rust para el rendimiento back-end y Electron para el diseño front-end, aprovechamos lo mejor de ambos mundos en el desarrollo de aplicaciones de escritorio.

```bat
# Estructura del proyecto (Árbol de carpetas en ASCII)
echo "
ETDC-App/
├── src/
│   ├── backend/
│   │   ├── main.rs           # Punto de entrada para Rust (lógica del servidor)
│   │   └── db.rs             # Gestión de base de datos
│   ├── frontend/
│   │   ├── assets/           # Imágenes, fuentes y otros recursos estáticos
│   │   ├── css/              # Hojas de estilo
│   │   ├── js/               # JavaScript para funcionalidad frontend
│   │   ├── components/       # Componentes reutilizables de la UI
│   │   └── index.html        # Página principal para Electron
│   └── common/
│       └── utils.rs          # Funciones utilitarias comunes
├── docs/
│   ├── setup.md              # Instrucciones de instalación
│   ├── usage.md              # Guía de uso
│   └── development.md        # Directrices para desarrolladores
├── tests/
│   ├── backend/
│   │   └── main_tests.rs     # Pruebas para la lógica de backend
│   ├── frontend/
│   │   └── ui_tests.js       # Pruebas para la interfaz de usuario
│   └── integration/
│       └── integration_tests.rs # Pruebas de integración para todo el sistema
├── tools/
│   ├── build.rs              # Scripts de compilación
│   └── deploy.sh             # Scripts de despliegue
├── .gitignore                # Especifica archivos no rastreados por git
├── LICENSE                   # Archivo de licencia
└── README.md                 # Información general y documentación del proyecto
"

```

- ## Fase de diseño y desarrollo

| Mes             | Actividad                                                    | Detalles                       |
| --------------- | ------------------------------------------------------------ | ------------------------------ |
| Julio 2024      | Planificación inicial                                        |                                |
| Agosto 2024     | Diseño de la arquitectura de software y prototipos iniciales |                                |
| Septiembre 2024 | Desarrollo inicial del backend en Rust                       |                                |
| Octubre 2024    | Integración de frontend y backend                            |                                |
| Noviembre 2024  | Pruebas unitarias y de integración                           | Preparación de la versión beta |
| Diciembre 2024  | Lanzamiento de la versión beta                               | Feedback de usuarios           |
| Enero 2025      | Lanzamiento oficial de la aplicación                         | Ajustes basados en el feedback |

## Enfoque en Tecnologías Avanzadas

Desde Arch Linux hasta Vim, el Elite Tech Dev Club (ETDC) se dedica a explorar herramientas y tecnologías que representan un verdadero desafío, asegurando una curva de aprendizaje inclinada. 

- **CyberDeck Personalizado**: Creación de un CyberDeck completamente funcional utilizando Linux y hardware personalizado. 
- **Corne Keyboard Personalizado**: Desarrollo de un teclado ergonómico y programable que use firmware de código abierto. Conocido por ser el favorito de usuarios avanzados
- **Distribución Linux Personalizada**: Creación de una distribución Linux personalizada enfocada en la seguridad y la optimización para desarrollo de software. Este proyecto podria ser desde la compilación del kernel hasta la configuración de sistemas de paquetes y gestión de ventanas.

``` bat
echo "
Elite Tech Dev Club (ETDC) Projects/
│
├── Desarrollo de Software Personalizado
│   ├── Desarrollo de un Sistema Operativo Minimalista
│   │   └── Crear un SO liviano y personalizable, enfocado en privacidad.md 
│   ├── Desarrollo de un Cliente de Tor Personalizado
│   │   └── Construir un cliente Tor con funcionalidades mejoradas.
│   └── Plataforma de Intercambio de Criptomonedas P2P
│       └── Crear una plataforma P2P para el intercambio de criptomonedas.
│
├── Hardware y Redes
│   ├── Creación de un Mesh Network Local
│   │   └── Implementar una red de malla como alternativa a ISPs tradicionales.
│   └── Desarrollo de Firmware Custom para Dispositivos Hardware Específicos
│       └── Firmware personalizado para dispositivos como teclados y routers.
|---Desarrollo de un Sistema Operativo Minimalista
│
└── Seguridad y Privacidad
    ├── Hacking Ético y Penetración de Redes
    │   └── Desarrollar técnicas y herramientas para pruebas de penetración.
    └── Sistema de Archivos Distribuidos
        └── Desarrollar un sistema que distribuya datos de forma segura y anónima.
 "
```

# Figma Prototipe