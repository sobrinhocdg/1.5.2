# ChosenOne - Dungeons RPG Mod for Minecraft 1.7.10

> **⚠️ PROJETO EDUCACIONAL - MOD DE TESTE**  
> Este é um projeto de aprendizado e desenvolvimento de mods para Minecraft. Não é um produto final comercial.

---

## 📋 Sobre o Projeto

**ChosenOne** é um mod educacional desenvolvido para fins de aprendizado em:
- Programação Java
- Modding de Minecraft (Forge 1.7.10)
- Geração procedural de mundo
- Inteligência Artificial de entidades
- Sistemas de loot e progressão

### 🎮 Características Principais

#### 🏰 **Dungeons com Múltiplos Andares (5-10)**
- Geração procedural subterrânea
- Substitui cavernas normais do jogo
- Cada andar é mais desafiador que o anterior
- Salas e corredores aleatórios

#### ⚔️ **10 Mobs Únicos por Tier**
| Andar | Mobs | Dificuldade |
|-------|------|-------------|
| 1-2 | Goblin, Skeleton Knight | Fácil |
| 3-4 | Orc Warrior, Dark Mage | Médio |
| 5-6 | Shadow Assassin, Fire Elemental | Difícil |
| 7-8 | Frost Giant, Void Walker | Muito Difícil |
| 9-10 | Dungeon Lord, Ancient Guardian (Bosses) | Épico |

#### 💎 **Sistema de Loot Progressivo**
- **Andares 1-2:** Itens básicos (ferro, comida)
- **Andares 3-4:** Diamantes, equipamentos
- **Andares 5-6:** Blocos de diamante, espadas encantadas
- **Andares 7-8:** Armaduras de diamante, pérolas do ender
- **Andares 9-10:** Blocos de esmeralda, itens lendários

#### ⛰️ **Geração de Mundo Aprimorada**
- Montanhas mais altas e dramáticas
- Picos gerados aleatoriamente
- Terreno mais desafiador para exploração

---

## 📥 Instalação

### Pré-requisitos
- **Minecraft 1.7.10** (versão exata)
- **Minecraft Forge 1.7.10** (build 10.13.4.1614 ou similar)

### Passos
1. Baixe o arquivo `chosenone-mod-V2.0-FINAL.jar`
2. Pressione `Win + R` no teclado
3. Digite: `%appdata%\.minecraft\mods`
4. Cole o arquivo `.jar` na pasta `mods`
5. Inicie o Minecraft com o perfil Forge 1.7.10
6. Crie um mundo novo e explore!

---

## 🛠️ Desenvolvimento

### Tecnologias Utilizadas
- **Linguagem:** Java 8
- **Framework:** Minecraft Forge 1.7.10
- **Build System:** Gradle (GTNH)
- **IDE:** Visual Studio Code / GitHub Codespaces

### Estrutura do Projeto

src/main/java/com/slime7/chosenone/
├── ChosenOne.java # Classe principal do mod
├── entity/ # Entidades (mobs)
│ ├── EntityGoblin.java
│ ├── EntitySkeletonKnight.java
│ ├── EntityOrcWarrior.java
│ ├── EntityDarkMage.java
│ ├── EntityShadowAssassin.java
│ ├── EntityFireElemental.java
│ ├── EntityFrostGiant.java
│ ├── EntityVoidWalker.java
│ ├── EntityDungeonLord.java
│ └── EntityAncientGuardian.java
└── world/
├── ChosenWorldGenerator.java # Geração de montanhas
└── structure/
└── DungeonGenerator.java # Geração de dungeons


### Como Compilar
```bash
# Clonar repositório
git clone https://github.com/sobrinhocdg/1.5.2.git

# Entrar na pasta do mod (GTNH)
cd minecraft-1.7.10-gtnh

# Compilar
./gradlew build -x checkstyleMain -x checkstyleTest

# O JAR estará em: build/libs/chosenone-*.jar

🎯 Funcionalidades Técnicas
Geração de Dungeons
Taxa de Spawn: 1 dungeon a cada ~30 chunks
Profundidade: Entre Y=30 e Y=100
Tamanho: Progressivo (5 + tamanho do andar)
Estrutura: Stone bricks com salas internas
IA dos Mobs
Pathfinding: Busca e ataque ao jogador
Spawning: Baseado no andar da dungeon
Comportamento:
Perseguição ao jogador
Wander aleatório
Attack on collide
Look idle (animação)
Sistema de Loot
Chests: Spawn aleatório por andar
Progressão: Loot melhora com a profundidade
Boss Drops: Itens exclusivos nos andares finais
📝 Versões
Versão
Data
Features
Status
V1.0.0
2026
Mobs básicos, dungeons simples
✅ Lançado
V2.0.0
2026
10 andares, 10 mobs, loot progressivo
✅ Final
V3.0.0
Em breve
Texturas personalizadas, sons, receitas
🚧 Planejado

🤝 Contribuição
Este é um projeto educacional e experimental. Contribuições são bem-vindas para:
Correção de bugs
Otimização de código
Novas features
Documentação
Como Contribuir
Fork o projeto
Crie uma branch (git checkout -b feature/AmazingFeature)
Commit suas mudanças (git commit -m 'Add AmazingFeature')
Push (git push origin feature/AmazingFeature)
Abra um Pull Request
⚠️ Avisos Importantes
Compatibilidade: Funciona apenas no Minecraft 1.7.10
Estabilidade: Projeto em desenvolvimento, pode conter bugs
Uso: Apenas para fins educacionais e de entretenimento
Suporte: Não há garantia de suporte contínuo
📄 Licença
Este projeto é distribuído como software educacional.
Sinta-se à vontade para estudar, modificar e aprender com o código.
🙏 Agradecimentos
Minecraft Forge Team - Framework essencial para modding
GTNewHorizons - Build system e templates
Comunidade de Modding BR - Suporte e aprendizado
📞 Contato
Desenvolvedor: Sobrinhocdg
GitHub: @sobrinhocdg
Projeto: github.com/sobrinhocdg/1.5.2
<div align="center">

Made with ❤️ for learning Minecraft Modding
ChosenOne Mod © 2026 - Projeto Educacional
</div>
