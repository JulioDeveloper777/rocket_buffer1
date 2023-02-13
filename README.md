### Simple Character System

### Simple Route Player
- Jogador conecta no servidor.
   - Jogador faz login no servidor.
      - Jogador cria ou escolhe um personagem criado.
         - Jogador é spawnado.
            
     
### Task list
- [X] Design da tela de criação de personagens.
- [X] Design da tela de seleção de personagens.
- [X] Sistema de criação de personagem.
- [X] Sistema de seleção de slot de personagem.

### Lista ordenada
1. Ao logar no servidor o jogador precisara fazer login.
2. Apos fazer login, a tela de seleção de personagens sera mostrada.
3. Estando na tela de seleção de personagens, o jogador podera criar ou selecionar um personagem criado.
4. Caso não tenha um personagem e deseje cria-lo, basta clicar no botão e ele irá para a tela de criação de personagens tendo que preencher o nome do personagem de ate 20 caracteres, idade do personagem de 2 caracteres, escolher um dos sexos pre-definidos e modificar as caracteristicas visuais do seu personagem, apos criá-lo preenchendo todas as informações corretamente, os dados preenchidos seram salvos e o jogador será spawnado com o personagem criado.
5. Ao deslogar e logar novamente no servidor, o personagem criado estará na tela de seleção de personagens exibindo o visual e nome do personagem, assim podendo clicar em selecionar e o jogador sera spawnado com o personagem escolhido.


### Show Character Info
1. Nome do personagem.
2. Personagem no cenario com todas as caracteristicas definidas.

### Save Data Character
1. Nome do personagem.
2. Idade do personagem.
3. Sexo do personagem.
5. Caracteristicas visuais do personagem.

### Permissions
- DeleteCharacter = OnlyAdmin;
- TransferCharacter = OnlyAdmin;
- EditDataCharacter = OnlyAdmin;

### Stacks
> Lua,
> Eventos,
> Formato de Desenho,
