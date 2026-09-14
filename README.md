# PlayerWatch

> Sistema de observação em primeira pessoa desenvolvido para operadores de servidores Minecraft.

O **PlayerWatch** permite que operadores acompanhem jogadores através da câmera em primeira pessoa, facilitando a observação de situações dentro do servidor sem interferir diretamente na gameplay.

---

## Recursos

* Observação em primeira pessoa de outros jogadores
* Restauração automática da localização e do gamemode anterior
* Encerramento manual da observação
* Encerramento automático quando o jogador observado sai do servidor
* Proteção contra observação de jogadores mortos
* Limpeza automática de sessões antigas
* Bloqueio de interação durante a observação
* Sistema de permissões
* Configurações diretamente no arquivo `.sk`

---

## Comandos

### `/watch <jogador>`

Inicia uma sessão de observação e conecta a câmera do operador à visão do jogador selecionado.

### `/watchstop`

Encerra a sessão de observação e restaura o estado anterior do operador.

---

## Configuração

O PlayerWatch possui configurações diretamente no arquivo `PlayerWatch.sk`:

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

---

## Requisitos

* Minecraft
* **Plugin Skript 2.16.2 ou superior**
* Nenhum addon adicional

> O **Skript é um plugin para servidores Minecraft** que adiciona uma linguagem de scripting, permitindo criar sistemas e funcionalidades através de arquivos `.sk`.

> O **PlayerWatch é um script desenvolvido para o plugin Skript**.

---

## Instalação

### 1. Instale o Skript

Certifique-se de que o **plugin Skript** está instalado no seu servidor.

### 2. Baixe o PlayerWatch

Baixe o arquivo `PlayerWatch.sk` pela seção **Releases** deste repositório.

### 3. Coloque o arquivo na pasta do Skript

```text
plugins/
└── Skript/
    └── scripts/
        └── PlayerWatch.sk
```

### 4. Recarregue o script

No console ou dentro do servidor:

```text
/sk reload PlayerWatch.sk
```

### 5. Pronto!

O PlayerWatch estará carregado e pronto para uso.

---

## Permissão

```text
playerwatch.use
```

Essa permissão é utilizada pelos comandos do PlayerWatch.

---

## Demonstração

O PlayerWatch permite acompanhar jogadores em primeira pessoa através do sistema de observação.

---

## Versão atual

**v1.0.0 — Primeira versão estável**

---

## PlayerWatch × Skript

O **PlayerWatch** foi desenvolvido como um script para o **plugin Skript**, utilizando sua linguagem de scripting para criar o sistema de observação em servidores Minecraft.
