# Guía de Contribución — CCIC

Las contribuciones externas a los repositorios del **Centro Colombiano para la Investigación Ciberfísica (CCIC)** deben adherirse a los siguientes principios de ingeniería:

1. **Soberanía y Dependencias Mínimas:** Evitar dependencias externas innecesarias. Todo código C++ debe compilar limpiamente bajo el estándar **C++17** con `-Wall -Wextra -Wpedantic`.
2. **Reproducibilidad:** Toda modificación en algoritmos numéricos o simulaciones debe incluir pruebas deterministas con semillas explícitas y documentación de métricas.
3. **Integridad de Historial:** Los *commits* deben ser atómicos, descriptivos y estar firmados criptográficamente (SSH o GPG).
