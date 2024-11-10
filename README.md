# Resolución de Problemas de Enrutamiento entre VLAN

Este proyecto documenta una serie de pasos para diagnosticar y resolver problemas comunes en la configuración de enrutamiento entre VLANs. La práctica se realiza en Cisco Packet Tracer y está enfocada en identificar y corregir errores que impiden la comunicación entre dispositivos en diferentes VLANs.

## Descripción del Proyecto

El propósito de esta práctica es simular y resolver problemas típicos de enrutamiento inter-VLAN. La habilidad para diagnosticar y corregir problemas en una red es crucial en entornos empresariales, donde la conectividad entre VLANs es esencial para la operación diaria.

## Objetivos de la Configuración

- Diagnosticar errores comunes en el enrutamiento entre VLANs, como asignaciones de IP incorrectas, problemas de configuración de subinterfaces y errores en la configuración de VLANs en switches.
- Aplicar técnicas de resolución de problemas para restaurar la conectividad entre dispositivos en diferentes VLANs.
- Probar la conectividad entre VLANs después de cada ajuste para confirmar que el problema se ha resuelto.

## Requisitos

Para poder realizar y revisar esta práctica, necesitas:

- **Cisco Packet Tracer** (versión 7.0 o superior).
- **Conocimientos en configuración de VLANs y enrutamiento inter-VLAN** en dispositivos Cisco.

## Archivos Incluidos

- **Resolucion_Problemas_Enrutamiento_VLAN.pka**: Archivo de Packet Tracer que incluye una configuración inicial con problemas para resolver.

## Instrucciones de Uso

1. Abre el archivo `.pka` en Cisco Packet Tracer.
2. Revisa la topología y las configuraciones de VLANs en el switch y el enrutador.
3. Utiliza herramientas como **ping** y **traceroute** para diagnosticar problemas de conectividad.
4. Realiza ajustes en la configuración del enrutador y del switch para resolver los problemas encontrados.
5. Prueba la conectividad después de cada corrección para asegurarte de que el enrutamiento inter-VLAN esté funcionando correctamente.

## Problemas Comunes y Soluciones

- **IP incorrectas en subinterfaces**: Verifica que cada subinterfaz tenga una dirección IP en el rango de la VLAN correspondiente.
- **Configuración de VLAN en el switch**: Asegúrate de que cada puerto esté correctamente asignado a la VLAN correspondiente.
- **Enlace troncal mal configurado**: Confirma que el enlace entre el switch y el enrutador esté configurado como troncal para permitir el tráfico de múltiples VLANs.

---

Esta práctica es una introducción a la resolución de problemas de enrutamiento entre VLANs. Es una excelente oportunidad para practicar habilidades esenciales en redes y prepararte para situaciones reales en entornos laborales. ¡Si tienes preguntas o recomendaciones, no dudes en compartir!
