# 📄 Informe Técnico del Taller

## 🔖 Nombre del Taller
_Taller 6 - Normatividad

## 👥 Integrantes del equipo
* Diego Ramírez – [diegorate@unisabana.edu.co](mailto:diegorate@unisabana.edu.co)
* Carlos Sánchez – [carlossanlo@unisabana.edu.co](mailto:carlossanlo@unisabana.edu.co)
* Mateo Vanegas – [mateovaco@unisabana.edu.co](mailto:mateovaco@unisabana.edu.co)

## 🧠 Descripción general del trabajo
El taller tuvo como propósito evaluar el grado de cumplimiento de las principales normativas de protección de datos y seguridad de la información aplicables a los sistemas empresariales.  
Durante la actividad se aplicó un checklist basado en la **Ley 1581 de 2012** (Protección de Datos Personales), la **Ley 1266 de 2008** (Habeas Data financiero) y el estándar **ISO/IEC 27001:2022**:contentReference[oaicite:0]{index=0}.  

El trabajo se desarrolló en dos fases: primero, se analizó el caso estatal *GobData* como modelo de referencia; luego, se adaptó el mismo instrumento al cliente real **Tekton Tech**, una empresa privada del sector BPO y desarrollo de software, identificando brechas, riesgos y recomendaciones priorizadas de cumplimiento.

## 🔧 Proceso de desarrollo
El equipo inició el taller revisando la plantilla de checklist utilizada en clase para el caso GobData, donde se discutieron los principales criterios de cumplimiento en torno a consentimiento, seguridad, retención de datos y roles de tratamiento.  
Posteriormente, se adaptó la estructura del checklist al contexto del cliente Tekton Tech, empleando como base la información ya recolectada del cliente.

El trabajo se realizó en Microsoft Excel, organizando los criterios según los marcos normativos revisados: **Ley 1581**, **Ley 1266**, y **ISO/IEC 27001:2022**:contentReference[oaicite:0]{index=0}.  
Cada integrante analizó una categoría (consentimiento, acceso, trazabilidad, retención, seguridad técnica), verificando su cumplimiento, evidencias y posibles brechas.

Finalmente, se consolidaron los hallazgos en una matriz de brechas y riesgos priorizada por nivel de criticidad, lo que permitió identificar los puntos más sensibles de cumplimiento y proponer acciones correctivas realistas para Tekton Tech.

## 🧩 Análisis del modelo propuesto

El modelo propuesto está compuesto por **dos instrumentos principales**:  
1. Un **Checklist de Cumplimiento Normativo**, que evalúa cada criterio legal y técnico asociado a la protección de datos, la seguridad de la información y la trazabilidad operativa.  
2. Una **Matriz de Brechas, Riesgos y Recomendaciones Prioritarias**, que clasifica los hallazgos según su impacto y urgencia de atención.

La estructura del checklist se diseñó para mantener una trazabilidad clara entre el criterio, su nivel de cumplimiento, la evidencia observada y la acción recomendada. Esto permite visualizar de forma inmediata el estado de cumplimiento de **Tekton Tech** frente a normas como la **Ley 1581 de 2012**, la **Ley 1266 de 2008** y la **ISO/IEC 27001:2022**:contentReference[oaicite:0]{index=0}.  
Cada fila representa un control o requisito evaluado, mientras que las columnas registran el nivel de madurez, justificación y recomendación concreta.

El modelo responde a las necesidades del cliente al enfocarse en los **procesos críticos** identificados en los informes anteriores: alta de clientes, facturación, conciliación y gestión documental. Las tablas reflejan brechas reales como la **ausencia de un Oficial de Protección de Datos (OPD)**, la **falta de trazabilidad centralizada** y la **inexistencia de políticas de retención o supresión de información**, todos puntos relevantes para la arquitectura actual de Tekton Tech.

Como supuesto general, se consideró que la empresa **utiliza plataformas SaaS** (por ejemplo, CRM y almacenamiento en la nube) sin un sistema centralizado de cumplimiento, y que los controles aplicados se encuentran en una **etapa de madurez intermedia**, lo que justifica las recomendaciones de fortalecimiento en políticas, roles y auditoría de accesos.


## 📈 Diagrama final entregado

A continuación se presentan las representaciones gráficas del trabajo desarrollado en el taller.  
La primera imagen muestra el **Checklist General de Cumplimiento Normativo**, y la segunda ilustra la **Matriz de Brechas y Riesgos Prioritarios** correspondientes al cliente Tekton Tech.

![Checklist General Tekton](Checklist-General-Tekton.png)

![Brechas Tekton](Brechas-Tekton.png)



## 🔍 Investigación complementaria
### Tema investigado:
**Normatividad colombiana y estándares internacionales aplicables a la protección de datos personales y seguridad de la información**

### Resumen:
Para complementar el taller se investigaron los principales marcos legales y técnicos que regulan el tratamiento de datos en Colombia y su relación con los estándares internacionales de seguridad.  
La **Ley 1581 de 2012** y su **Decreto Reglamentario 1377 de 2013** establecen los principios de legalidad, libertad, veracidad, transparencia, seguridad y confidencialidad en el uso de datos personales, junto con la obligación de obtener consentimiento informado y definir los roles de Responsable, Encargado y Oficial de Protección de Datos (OPD).  
La **Ley 1266 de 2008** regula la administración de datos financieros y crediticios, garantizando su actualización y veracidad.  
Por su parte, el estándar **ISO/IEC 27001:2022** proporciona el marco de referencia para la gestión de seguridad de la información, incluyendo políticas de acceso, trazabilidad, cifrado y auditoría:contentReference[oaicite:0]{index=0}.

Estas normas se integran en el contexto empresarial de **Tekton Tech** como lineamientos para diseñar una arquitectura que salvaguarde la privacidad, gestione riesgos de fuga de información y mantenga la confianza de clientes y aliados.  
El uso conjunto de estos marcos permite establecer un **Sistema de Gestión de Seguridad de la Información (SGSI)** alineado con la legislación nacional y las mejores prácticas internacionales.


### Resumen:

La investigación se centró en comprender el alcance de las principales **normas de protección de datos y seguridad de la información** aplicables en Colombia y su vínculo con marcos internacionales.  
La **Ley 1581 de 2012** y el **Decreto 1377 de 2013** establecen los principios fundamentales del tratamiento de datos personales —legalidad, finalidad, libertad, veracidad, transparencia, seguridad y confidencialidad— además de exigir consentimiento informado y definir roles de tratamiento (Responsable, Encargado y Oficial de Protección de Datos):contentReference[oaicite:0]{index=0}.  
En paralelo, la **Ley 1266 de 2008** regula los datos financieros y crediticios, reforzando la obligación de mantener información veraz y actualizada frente a terceros y entidades de control.

A nivel técnico, el estándar **ISO/IEC 27001:2022** aporta un marco estructurado para la **gestión de la seguridad de la información**, incluyendo políticas de acceso, control de incidentes, trazabilidad y mejora continua. Su adopción permite evidenciar cumplimiento ante auditorías y reducir riesgos operativos:contentReference[oaicite:1]{index=1}.  

En el contexto del taller, estas referencias sirvieron para **construir el checklist y la matriz de brechas** aplicados al cliente real *Tekton Tech*. Dichos instrumentos tradujeron los requisitos legales y los controles técnicos en criterios medibles, lo que permitió evaluar el nivel de madurez en cumplimiento y proponer acciones concretas para fortalecer la arquitectura de seguridad y protección de datos de la empresa.


## 📚 Referencias

- [1] Congreso de la República de Colombia. *Ley 1581 de 2012 – Por la cual se dictan disposiciones generales para la protección de datos personales.* Diario Oficial No. 48.587, 17 de octubre de 2012.  
- [2] Presidencia de la República de Colombia. *Decreto 1377 de 2013 – Reglamentario de la Ley 1581 de 2012.* Diario Oficial No. 48.834, 27 de junio de 2013.  
- [3] Congreso de la República de Colombia. *Ley 1266 de 2008 – Habeas Data Financiero.* Diario Oficial No. 47.219, 31 de diciembre de 2008.  
- [4] International Organization for Standardization (ISO). *ISO/IEC 27001:2022 – Information security, cybersecurity and privacy protection — Information security management systems — Requirements.* Geneva: ISO, 2022.  
- [5] Ministerio de Tecnologías de la Información y las Comunicaciones (MinTIC). *Guía para la Implementación de la Ley de Protección de Datos Personales (Ley 1581 de 2012).* Bogotá D.C., 2021.  
- [6] Universidad de La Sabana. *Apuntes de clase: Normatividad y Cumplimiento en Arquitectura.* Curso AREM – Arquitectura Empresarial, 2025:contentReference[oaicite:0]{index=0}.


---

_Este documento hace parte de la entrega del taller 6 del curso AREM (Arquitectura Empresarial) - Universidad de La Sabana._
