# Varginha Files — Ecos do Silêncio

Survival horror 3D em primeira pessoa ambientado em Varginha, Minas Gerais, em 1996.

## Visão
Jogo autoral inspirado no ritmo de exploração, gerenciamento de recursos e combate de survival horror moderno, com investigação paranormal e identidade própria. Não utilizar personagens, assets, marcas, mapas ou interfaces copiados de franquias existentes.

## Tecnologia
- Unreal Engine 5 (projeto C++ com suporte a Blueprints)
- Plataforma inicial: Windows
- Controle de versão: Git e Git LFS para assets binários rastreados
- Idioma principal: português do Brasil

## Vertical slice — Capítulo 1: O Chamado
1. Max Morgan chega a uma estrada rural durante uma tempestade.
2. Jogador explora em primeira pessoa, usa lanterna e registra pistas.
3. Encontra arma e munição escassa; enfrenta a primeira ameaça no galpão.
4. Explora uma casa abandonada e localiza documentos.
5. Enfrenta perseguição e termina diante de uma instalação militar.

### Critérios para o primeiro protótipo
- Personagem se movimenta, corre, agacha e olha em primeira pessoa.
- Sistema reutilizável de interação com objetos.
- Pistola funcional, mira, tiro, recarga, vida e dano.
- Inventário em grade com rotação, colisão e salvamento.
- Uma criatura de teste com patrulha, detecção e ataque.
- Um mapa simples jogável do começo ao fim usando placeholders.

## Inicialização no computador
1. Instalar Unreal Engine 5 e Visual Studio com componentes C++ para jogos.
2. Criar no Unreal Editor um projeto **Games > First Person > C++**, nome **VarginhaFiles**, sem Starter Content, na pasta local deste repositório.
3. Fechar o Editor, conferir o `.gitignore`, inicializar Git LFS e versionar os arquivos-fonte.
4. Abrir o repositório no Codex e implementar cada sistema em entregas pequenas.
5. Fazer testes no Unreal Editor local; commits não garantem compilação sem o motor instalado.

**Importante:** este repositório contém neste momento apenas documentação e preparação. O arquivo `.uproject` ainda precisa ser criado no Unreal Editor.
