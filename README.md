# Scripts de Cloud Formation

## Pendências

### moodle-single-alarm.json
1. Criar uma configuração para realizar o backup em S3
2. Adicionar a permissão no perfil do IAM para que possibilite a escrita e leitura no S3
3. Criar uma forma de restaurar backup durante o boot

### moodle-cluster.json
1. Remover sticky session do load balancer
2. Criar o registro de DNS para acessar o load balancer
3. Ajustar o boot para fazer upgrade de banco de dados durante a subida
4. Cria o certificado para o endereço sendo provisionado
5. Atribuir o certificado ao load balancer e abrir HTTPS
6. Verificar a necessidade de criar a configuração no nginx para redirecionar para https