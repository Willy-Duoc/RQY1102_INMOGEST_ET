## INMOGEST

Proyecto de Software de Gestión Integral para la administración del edificio Mirador.

## Integrantes

* Williams Contreras - Arquitecto de Software / Backend Developer
* Horacio Navarrete - QA Lead / Frontend Developer

## Problema

La administración del edificio Mirador presenta deficiencias importantes en la gestión diaria: falta de transparencia en el manejo de los activos y gastos comunes, procesos administrativos ineficientes y una comunicación deficiente entre administración y residentes. La operación se realiza de forma manual, apoyada en bitácoras físicas y canales informales lo que dificulta la trazabilidad de la información.

Esta situación ha generado desconfianza entre los copropietarios, conflictos vecinales, posibles fugas de dinero y dificultades para ejecutar correctamente los proyectos de mantención del edificio.

## Solución Propuesta

INMOGEST es un sistema web que centraliza y digitaliza la gestión administrativa del edificio Mirador, reemplazando los procesos manuales por una plataforma única y transparente.

El sistema permite a los residentes:
- Consultar su estado de cuenta y el detalle de sus gastos comunes.
- Realizar pagos en línea a través de una pasarela de pagos externa.
- Registrar solicitudes de mantención y quejas, y hacer seguimiento a su estado.
- Comunicarse con la administración y conserjería.

Y permite a la administración:
- Calcular y emitir automáticamente los cobros mensuales.
- Identificar residentes morosos y generar alertas.
- Gestionar incidencias, solicitudes y personal del edificio.
- Generar reportes financieros y operativos, y exportarlos en distintos formatos.
- Mostrar un panel de transparencia con el uso de los recursos del edificio.

Técnicamente, INMOGEST se implementa como una aplicación web bajo el patrón arquitectónico MVC (Modelo-Vista-Controlador), en tres capas: presentación, lógica de negocio y acceso a datos, con autenticación mediante JWT y autorización basada en roles (Administrador, Propietario, Arrendatario, Conserje).

Con esta solución se busca aumentar la liquidez del edificio, mejorar la satisfacción de los residentes, reducir la morosidad y fortalecer la confianza entre administración y comunidad.

## Enlace del Prototipo

https://www.figma.com/make/AFUzbMgrijKhyKpiMureZl/Prototipo-Inicial-Inmogest?t=5mOw4qXAPUCtHAww-1
