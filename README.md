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
* **Skript 2.16.2 ou superior**
* Nenhum addon adicional

> O PlayerWatch é um **script desenvolvido para o plugin Skript**.

---

## Instalação

### 1. Baixe o PlayerWatch

Baixe o arquivo `PlayerWatch.sk` pela seção **Releases** deste repositório.

### 2. Coloque o arquivo na pasta do Skript

```text
plugins/
└── Skript/
    └── scripts/
        └── PlayerWatch.sk
```

### 3. Recarregue o script

No console ou dentro do servidor:

```text
/skr reload PlayerWatch
```

### 4. Pronto!

O PlayerWatch estará carregado e pronto para uso.

---

## Permissão

```text
playerwatch.use
```

Essa permissão é utilizada pelos comandos do PlayerWatch.

---

## Tutorial

### Instalação

Adicione aqui uma imagem mostrando o processo de instalação.

### Utilização

Adicione aqui uma imagem mostrando o PlayerWatch em funcionamento.

---

## Versão atual

**v1.0.0 — Primeira versão estável**

---

## PlayerWatch × Skript

Desenvolvido como um script para o plugin **Skript**, utilizando sua linguagem de scripting para Minecraft.
