# DesafioDioAzure2

🚀 Passo a Passo: Criar uma instância do Azure SQL Database


Criar um recurso
    No menu esquerdo, clique em "Criar um recurso".
    Escolha "Bancos de dados" > "SQL Database".

Configurando a instância
    Selecione a assinatura da Azure(ela quem deficne quais recursos você pode criar)
    Criar um novo grupo de recursos(é como uma pasta src)    
    Criar um servidor:
        Nome do servidor (único)
        Região (escolha uma próxima a você).
        Metodo de autenticação. (Como você vai acessar o servidor)
        Defina um administrador do servidor.
Escolhendo o melhor plano.
        Clique em "Configurar banco de dados" para escolher o tipo de desempenho (ex: DTU ou vCore).
        Para testes, você pode usar o Plano Gratuito (se disponível) ou mais barato, como "Basic"

 Segurança e conectividade
         Defina se o acesso vai ser publico ou privado
         Defina as politicas de conexão
         Defina como será a proteção dos seus dados.

Revisão
        Antes de clicar em criar revise suas configurações.
        Após isso clique em "criar" e sua instancia estará online em instantes.
            
