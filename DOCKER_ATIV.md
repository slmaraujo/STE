Aqui está a configuração formatada para GitHub:


# DOCKER_CONFIGURAÇÃO

## ATIVIDADE DOCKER_AWS

### PRIMEIRO FOI CRIADO A VPC
- VPC_DOCKER_ATIVIDADE
  - ID: vpc-061d550d53b75b162

### CONFIGURAÇÃO SUBREDES

#### Pública:
- Nome: PUBL_SUB
- Bloco CIDR: 10.0.1.0/24
- IPV4: 251
- ID: subnet-0eb01ec4a79d0cc6d

#### Privada:
- Nome: Priv_Sub
- Bloco CIDR: 10.0.2.0/24
- IPV4: 251
- ID: subnet-0dfec2ce951469e83

### ASSOCIANDO GATEWAY A VPC
- GATEWAY: GATEWAY_DOCKER

### CRIANDO TABELA DE ROTA E ASSOCIANDO A VPC
- Nome: PUBL_ROUTE_TABLE
- ID: rtb-0c9ee6d4c5f8740f9
- Vincule ela ao Gateway criado

### CRIANDO SECURITY GROUP
- Nome: DOCKER_SECURITY_GROUP
- ID do Grupo de Segurança: sg-0095ecbdd9000ac5e
```
