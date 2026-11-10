# OptiPrint-Finance: Plataforma Web SaaS de Optimización Financiera

**Estudiante:** Marial Gabriela Rodas Chambi  
**Docente:** Brigida Alexandra Carvajal Blanco  
**Materia:** Métodos Numéricos  
**Mención:** Desarrollo de Sistemas e Innovación Tecnológica  
**Universidad:** Universidad Mayor de San Andrés (UMSA)  

 Descripción del Proyecto
Este proyecto es una plataforma web interactiva que resuelve un modelo matemático de asignación óptima de recursos financieros para una imprenta digital y tienda de comercio electrónico (OptiPrint). 

Se utiliza el **Método de Gradientes Conjugados Precondicionado (GCP)**, fundamentado en el artículo de Suñagua (2020), para resolver un sistema lineal simétrico y definido positivo \(Ax = b\) con 4 variables de presupuesto (insumos, logística, pasarelas de pago y marketing).

 Arquitectura del Sistema
El proyecto está construido como una **Single Page Application (SPA)** utilizando tecnologías web nativas, sin necesidad de un servidor backend:
*   **HTML5 & CSS3:** Interfaz de usuario responsiva con diseño en tonos rosa y celeste.
*   **JavaScript (Vanilla):** Motor numérico que incluye factorización de Cholesky, Gradientes Conjugados, Gradientes Conjugados Precondicionados, y cálculo de autovalores para verificar la matriz.
*   **KaTeX:** Renderizado de fórmulas matemáticas de alta calidad.
*   **Canvas API:** Generación dinámica de gráficos de convergencia y errores.

 Instrucciones de Instalación y Ejecución Local
Dado que es una aplicación web estática, no requiere instalación de dependencias ni gestores de paquetes.

1. Descarga o clona este repositorio:
   ```bash
   git clone https://github.com/GABIALHUB/METODO_GRADIENTE-_AREA_FINANCIERA.git
