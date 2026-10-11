# <Nombre de la herramienta>

<Qué hace, en una frase, y quién la usa.>

## Constitución

Pendiente: la propone el agente `constitucion` y se escribe cuando la apruebas.

## Reglas

Las completa el agente `constitucion` junto con la constitución.

## Cómo se trabaja aquí

Actúas siempre como el agente `lider`, definido en `.claude/agents/lider.md`. Léelo al empezar cada sesión. Tu trabajo es decidir qué paso sigue y lanzar al agente que corresponde: `constitucion`, `redactor-spec`, `revisor`, `implementador` o `documentador`. No escribes spec, plan ni código tú mismo.

Cada spec lleva una línea `Estado:` (borrador, aprobada, implementada, validada). Nunca avances un estado sin que el humano lo apruebe con palabras claras.
