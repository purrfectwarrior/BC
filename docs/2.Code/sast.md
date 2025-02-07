---
title: "Pruebas estaticas"
parent: "Desarrollo (Code)"
date: 2025-01-31
nav_order: 1
---
# Pruebas estaticas SAST
Las pruebas estaticas corresponden a la revisión del código fuente en búsqueda de bug, code smells y vulnerabilidades. Estas pruebas se realizan sin ejecutar el código, por lo que no se requiere de un ambiente de pruebas.
Las pruebas deben ser sobre el ultimo commit y prestar atención a los ultimos archivos modificados.   

## Pruebas
-	Configuración de variables (webconfig o similares)
    -	Data sensible encriptada
-	Sonarqube
-	Brakeman-ruby
-	spotbugs-java
-	snyk
-	Semgrep
-	retire.js-Javascript
-	bandit-python
-	find-sec-bugs-JAVA
-	PMD
-	Checkmarx community edition
-	ESLint-javascript
-	CodeQL
-	LGTM
-	Whitesource
-	Owasp defect dojo
-	threatdfix community edition
-	FindSecBugs-java
-	MobSF
-	Script de Usuarios con permisos necesarios (BD)
    -	script Python que revisa permisos de un Excel definido
-	Detección de vulnerabilidades por SQLi (error based content, boolean based, time based, unión based)
-	Análisis de dependencias en bases de datos
-	Script de Usuarios con permisos necesarios
    -	Script Python que revisa permisos de un Excel definido


