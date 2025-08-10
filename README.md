# Desafio docker 1 Full
## Docker

### 1.1 - Go Lang e Docker

O objetivo deste desafio é criar uma imagem Docker que, ao ser executada, exibe a mensagem "Full Cycle Rocks!!". A imagem precisa ter menos de 2MB.

#### Imagem

- [Docker Registry](https://hub.docker.com/r/lucaskohlermarques/full-cycle-rocks)

#### Validação

Execute o comando:

```bash
docker run -it --name full-cycle-rocks lucaskohlermarques/fullcycle
```

Output esperado:

```bash
Full Cycle Rocks!!
```
