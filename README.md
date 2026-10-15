# Jarvis Ultra — canal oficial de actualizaciones

Este repositorio público distribuye exclusivamente versiones instalables de **Jarvis Ultra para Windows**.

El código fuente permanece privado en [AntonioBonache/Jarvis](https://github.com/AntonioBonache/Jarvis).

## Estado

**Aún no hay instalador publicado.** La primera versión se distribuirá aquí tras compilarla en Windows, realizar pruebas y configurar la firma criptográfica.

Los lanzamientos contendrán, como mínimo:

- `JarvisUltra-Setup-X.Y.Z.exe`: instalador para Windows.
- `latest.json`: manifiesto de versión firmado mediante Ed25519, con hash SHA-256 del instalador.

El actualizador del programa verificará el manifiesto y el instalador antes de ejecutar nada, y te pedirá confirmación. Esta firma de actualizaciones **no equivale a una firma Authenticode de Windows**.

No publiques aquí claves privadas, datos personales, tokens OAuth ni código privado. Nunca desactives Smart App Control o Defender para instalar un ejecutable bloqueado.

Consultar [Releases](https://github.com/AntonioBonache/Jarvis-Releases/releases) cuando aparezca el primer instalador oficial.
