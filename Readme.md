 # Taller 3 Programación Orientada a objetos: conceptos básicos de POO, diag. clases y Java.  

### Desarrollador: `Diego Labrin` 

 ### Principales clases identificadas: 

- Clase Atleta: 
  - Asociación con Disiplina de multiplicidad 0..*
  - Asociación con Equipo de multiplicidad 1..*
  - Asociación con Equipo de multiplicidad 0..1
- Clase Equipo:
  - Composición con Atleta de multiplicidad 1..*
  - Composición con Atleta de multiplicidad 1..*
- Clase Disiplina:
  - Asociación con Atleta de multiplicidad 1..*
  - Asociación con Evento de multiplicidad 1
- Clase Evento:
  - Composición con Atleta de multiplicidad *
  - Asociación con Equipo de multiplicidad 1..*
  - Asociación con Atleta de multiplicidad 1..*
