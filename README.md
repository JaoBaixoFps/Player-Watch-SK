# PlayerWatch

Sistema de observação em primeira pessoa desenvolvido para operadores de servidores Minecraft.

O **PlayerWatch** permite que operadores acompanhem jogadores através da câmera em primeira pessoa, facilitando a observação de situações dentro do servidor sem interferir diretamente na gameplay.

## Recursos

* Observação em primeira pessoa de outros jogadores
* Restauração automática da localização e do gamemode anterior
* Encerramento manual da observação
* Encerramento automático quando o jogador observado sai do servidor
* Proteção contra observação de jogadores mortos
* Limpeza automática de sessões antigas
* Bloqueio de interação durante a observação
* Sistema de permissões
* Configurações através do próprio arquivo `.sk`

## Comandos

```text
/watch <jogador>
```

Inicia uma sessão de observação.

```text
/watchstop
```

Encerra a sessão atual e restaura o estado anterior do operador.

## Configuração

O PlayerWatch possui opções diretamente no arquivo `PlayerWatch.sk`:

```text
enabled: true
show-load-message: true
operator-only: true
stop-on-target-quit: true
```

### `enabled`

Ativa ou desativa o sistema.

### `show-load-message`

Define se uma mensagem será enviada ao console quando o sistema for carregado.

### `operator-only`

Define se o PlayerWatch deve ser restrito a operadores.

### `stop-on-target-quit`

Define se a observação deve ser encerrada automaticamente quando o jogador observado sair do servidor.

## Requisitos

* Minecraft
* [Skript](https://github.com/SkriptLang/Skript) **2.16.2 ou superior**

Nenhum addon adicional é necessário.

## Instalação

1. Baixe o arquivo `PlayerWatch.sk`.
2. Coloque-o em:

```text
plugins/Skript/scripts/
```

3. Recarregue o script:

```text
/skr reload PlayerWatch
```

4. O PlayerWatch estará pronto para uso.

## Permissão

```text
playerwatch.use
```

A permissão utilizada pelos comandos do sistema é:

```text
playerwatch.use
```

## Versão atual

**v1.0.0 — Primeira versão estável**

---

Desenvolvido para facilitar a observação e administração de servidores Minecraft.
