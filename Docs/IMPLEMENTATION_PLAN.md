# Plano técnico para Codex + Unreal Engine 5

## Ordem de implementação (PRs pequenas)
1. **Base C++ e Enhanced Input:** personagem FPS, movimento, corrida, agachamento, câmera, entradas configuráveis.
2. **Interação:** interface de interação, line trace, prompt HUD e pickups.
3. **Combate:** componente de saúde, arma base, pistola, munição, recarga, disparo e feedback.
4. **Inventário:** estruturas de dados, maleta em grade com rotação, validação de sobreposição, UMG.
5. **Investigação:** pistas, câmera fotográfica, diário e objetivos.
6. **IA:** uma criatura de teste com comportamento de patrulha/detecção/perseguição.
7. **Fase:** graybox da estrada, trilha, galpão, casa e clareira; gatilhos de narrativa.
8. **SaveGame e acabamento:** saves, menus, áudio, testes e empacotamento Windows.

## Convenções
- Módulo: VarginhaFiles
- Prefixos: A para Actors, U para Objects/Components, F para structs, E para enums.
- Blueprints visuais: `BP_`; interfaces: `BPI_`; Widgets: `WBP_`; mapas: `L_`.
- Pastas em `Content/VarginhaFiles/`: Characters, Weapons, Inventory, Investigation, AI, UI, Maps, Audio, Environment.
- Dados devem ser orientados a Data Assets quando conveniente.
- Não editar arquivos binários sem o editor; codificar componentes C++ e descrever ligações Blueprint necessárias.
- Sem geração de grandes binários no Git normal: Git LFS para assets com rastreamento.
- Não afirmar compilação ou jogabilidade sem validação real no editor.

## Definição de pronto — milestone 0.1
- Compila no projeto UE5 local.
- Controles de câmera/movimento em teclado e mouse.
- Pistola de teste atira com munição e recarga verificáveis.
- Uma caixa de item coletável e inventário abrível.
- Mapa graybox de teste abre e tem início/fim.
- README de configuração atualizado com versão exata do motor.
