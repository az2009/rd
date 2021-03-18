![RaiaDrogasil](https://media-exp1.licdn.com/dms/image/C560BAQEHYVN7WGADHg/company-logo_100_100/0/1519869614526?e=1623888000&v=beta&t=ypBOUzzjt0PT6CzkN9_5uCf3haNrYY9ZanBikfxwC88)
========      
Teste para avaliar as habilidades dos candidatos a Magento Backend Developer.

# Introdução
Este teste de avaliação tem como objetivo avaliar seu conhecimento como desenvolvedor Magento Backend. O teste de avaliação avaliará suas habilidades em:

- Seu nível de conhecimento da linguagem PHP OOP (PHP versão 7 +)
- Arquitetura de componentes Magento (Magento Open Source / Commerce 2.3+)
- Conhecimento dos principais padrões de design usados ​​pela plataforma
- Uso de injeção de dependência
- Plugins Magento (Interceptores)
- Padrões de código e boas práticas de programação
- Princípios SOLID e recomendações de padrões PHP (PSR)
- Composer

# O que será avaliado?
- Estrutura e organização de código e arquivos
- Soluções adotadas
- Tecnologias utilizadas
- Qualidade
- Padrões PSR

# Como publicar seu teste?
- Crie um repositório público no GitHub
- Faça o push do seu módulo para o repositório
- Quando terminar envie a URL do repositório para o contato que está direcionando o processo seletivo

# Instruções
O foco principal do nosso teste de avaliação é avaliar suas habilidades e conhecimentos como desenvolvedor Magento Backend.
Você tem total liberdade para aumentar alguns conhecimentos que considere interessantes para aplicar na avaliação.

>Não há problema se você não conseguir executar todos os recursos da avaliação, faça o máximo que puder.

##Recursos básicos
1. Módulo para criar entidade Sellers que irá armazenar os dados dos vendedores cadastrados no Marketplace;
2. Use interfaces para criar contratos de serviço;
3. O módulo deve ter recursos para criar, editar, listar e deletar vendedore através da área de administração do Magento;
4. O acesso ao módulo deve estar disponível na área Magento Admin através do menu 'Content > Sellers';
5. Deve ser possível restringir o acesso a usuários Magento Admin para criar, editar, excluir e listar vendedores;
6. O formulário de registro do vendedor deve ter:

| Field name       | Type        | Required | Additional checks                |
|------------------|-------------|----------|----------------------------------|
| Enable           | bool        | Yes      |                                  |
| Company Name     | text        | Yes      | Alfanumérico, Max. 200 Carácteres|
| CNPJ             | varchar     | Yes      | Max. 15 Carácteres               |
| Description      | textarea    | No       | Max. 600 Carácteres              |
| Logo Image       | file/UI     | Yes      | PNG or JPG                       |

7. Configure um atributo de produto dropdown para selecionar o vendedor por nome ao criar um novo produto na área de administração do Magento;
8. O atributo do produto deve ser criado por meio da configuração do módulo, se possível remover o atributo vendedor ao desinstalar o módulo de Seller;
9. O atributo dropdown vendedor deve listar apenas vendedores cadastrados que possuem Enable = true;
10. Tradução para todos os rótulos e textos com i18n;

## Recursos Avançados
1. Importar registros de vendedores via arquivo CSV usando o comando MAGENTO CLI
2. Disponibilizar no GraphQl a consulta de vendedores por ID
3. Todo o código deve passar nos testes estáticos do Magento (padrões de codificação do Magento)
4. Criar testes de unidade para cobrir pelo menos 03 classes (01 Model, 01 Block e 01 Controller)
5. Criar Grid e Formulário de cadastro do Vendedor via Magento UI Component





