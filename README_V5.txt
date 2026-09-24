GENERADOR DE MENÚ V5
====================

Novetats:
- Base inicial incorporada des de Menús(3).xlsx (108 plats).
- Ja no cal carregar cap Excel per generar el menú.
- Botó "Gestionar plats": buscar, afegir, editar i eliminar.
- Restaurar els 108 plats originals.
- Exportar/importar una còpia JSON dels plats modificats.
- Manté els criteris configurables i genera una sola proposta de 28 dies.

PROVA LOCAL A WINDOWS
1. Descomprimeix el ZIP en una carpeta nova, per exemple:
   C:\FVO\Generador_Menu_PWA_V5
2. Obre CMD dins la carpeta.
3. Executa: python -m http.server 8096
4. Obre Chrome: http://localhost:8096/index.html
5. Prova "Gestionar plats" i després "GENERAR NOVA PROPOSTA".

IMPORTANT
- Els canvis de plats i criteris es guarden localment al navegador/dispositiu.
- "Exportar còpia" permet guardar els plats modificats i "Importar còpia" recuperar-los en un altre dispositiu.
- La sincronització automàtica entre dispositius serà una fase posterior.
