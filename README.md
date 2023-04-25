# Laboratório de Redes - FairyDGames
Atividade de Docker da disciplina de Lab. de Redes, com destaque para a pseudoempresa FairyDGames.
# Informações do Aluno
Aluno: Raul Miguel Santos Nascimento
Disciplina: COMP0463 - LABORATÓRIO DE REDES DE COMPUTADORES (2022.2 - T01)
Professora: Edilayne Meneses Salgueiro

### Pré-comandos
```
git clone https://github.com/Raulshadow/FairyDGames_Etapa4_Raul.git
```

```
cd FairyDGames_Etapa4_Raul.git
```

### Build:
```
docker build -t fairydgames .
```
### Execução como Servidor:
```
docker run -d fairydgames
```

### Descobrir o Container ID do container executado com o servidor
```
docker ps
```

### Testando a aplicação
```
docker exec ba4e23bf3fdd python TCPClient.py
```

### Verificar informações do container
```
docker exec -i -t ba4e23bf3fdd /bin/bash
```
