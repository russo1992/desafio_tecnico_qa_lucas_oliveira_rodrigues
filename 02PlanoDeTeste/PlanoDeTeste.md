Descrição
Plano de Testes
Informações gerais :

 

# Visão geral
<br/>

 ## Um plano de testes para clarificar a todos envolvidos o que será testado.
<br/>

## Identificador único
<br/>

#0002
<br/>

## Organizador responsável
<br/>

* Lucas Oliveira Rodrigues
<br/>

## Aprovadores
<br/>

Fulano de tal da Fidelity Pesquisas Cadastrais (QA Specialist)
<br/>
 

Histórico de mudanças

* 21/Fevereiro/2025 crie o Plano 
* 21/Fevereiro/2025 finalizei o Plano
<br/>
 

## Escopo geral
<br/>

* Projeto do Autenticator

* Teste Funcional do Autenticator
<br/>

## Não está no escopo da User Story do Autenticator testar as funcionalidades de:
<br/>

N/A
<br/>
 

## Referências
<br/>

Mapa mental do Autenticator.

(![alt text](<../assets/mapa mental desafio tecnico.png>))

 

<br/>
 
 
Glossário de Termos



 

Contexto do teste

 

Projetos ou Sub-processos de Teste

Autenticator
<br/>
 

## Itens de teste
<br/>

Autenticator
<br/>
 

## Escopo do teste
<br/>

**Serão Testados:**
<br/>

* Autenticator Funcional (Tela login)


<br/>
 

## Não serão testados:
<br/>

* N/A

<br/>


## Stakeholders
<br/>

* Fulano de tal da Fidelity Pesquisas Cadastrais(QA Specialist)
<br/>


## Registro de risco de comunicação de teste :
<br/>
 

* Riscos do produto

* Cobertura Incompleta de Testes : ( testes manuais podem deixar passar alguns cenários ) .

* Erros Humanos : (O teste manual está sujeito a erros humanos e pode haver inconsistência na forma como os testes são realizados) .

* Rastreabilidade : (Pode ser difícil rastrear quais testes foram executados, quais cenários foram cobertos, e quais resultados foram obtidos) .

<br/>
 

## Riscos do projeto
<br/>

*  Devida a pouca experiência , esse plano possa ter a execução ineficiente de testes e planejamento de testes inadequado .

 

## Estratégia de teste :
<br/>
 

* O planejamento de testes para o  Autenticator visa garantir que todas as funcionalidades sejam testadas de forma abrangente e estruturada .
<br/>

## Teste de sub-processos
<br/>

* Autenticator
<br/>
 

## Entregáveis de teste
<br/>

* Plano de teste ;

* Cenário Macro ;

* Matriz de rastreabilidade ;

* Relatório de teste ;

* Critérios para Seleção de Testes para Automação .


 <br/>

## Técnicas de teste
<br/>

* Partição de Equivalência ;
* Valor Limite ;

<br/>
 

## Critérios de conclusão de teste
<br/>

* 100% dos incidentes com prioridade média , alta e critica , foram corrigidos e fechados
<br/>

## Métricas a serem coletadas .
<br/>

* 100% de defeitos corrigidos e fechados .
<br/>
 

## Requisitos de dados de teste
<br/>

* Que a tela de login do Autenticator já esteja pronta .
<br/>
 

## Requisitos do ambiente de teste
<br/>

* Os testes serão realizados exclusivamente na web, utilizando o Autenticator disponível.
  

<br/>

## Novos testes e testes de regressão
<br/>

* Novos testes a cada nova entrega

* Testes regressivos antes da entrega para a próxima fase
<br/>
 

## Critérios de suspensão e retomada
<br/>

* Autenticator ficar sem a construçao da tela de  login por mais de 3 dias (Suspensão)

* Autenticator foi feita a criação da  tela de login (está feita) por mais de 24 horas (Retomada)
<br/>
 

## Desvios da Estratégia de Teste Corporativa
<br/>

* Nesse projeto, dado a pequena quantidade a ser testada , será necessário só um testador .
<br/>
 

## Cenários Macro
<br/>
              Funcional
<br/>

* Cenário 1 : Registro bem-sucedido 
* Cenário 2 : Registro com e-mail já cadastrado
* Cenário 3 : Registro com senha fraca
* Cenário 4 : Registro com e-mail inválido 
* Cenário 5 : Login bem-sucedido
* Cenário 6 : Logout bem-sucedido
* Cenário 7 : Login com usuario em branco
* Cenário 8 : Login com senha vazia
* Cenário 9 : Login com senha no formato certo mas minuscula
* Cenário 10 :Login bem-sucedido após redefinição de senha 

<br/>

        

## Matriz de Rastreabilidade
<br/>

# Matriz de Rastreabilidade de Testes

| **ID do Cenário** | **Descrição**                                          | **Status**      |
|-------------------|--------------------------------------------------------|-----------------|
| **Cenário 1**      | Registro bem-sucedido                                 | Passou          |
| **Cenário 2**      | Registro com e-mail já cadastrado                     | Passou          |
| **Cenário 3**      | Registro com senha fraca                              | Passou          |
| **Cenário 4**      | Registro com e-mail inválido                          | Passou          |
| **Cenário 5**      | Login bem-sucedido                                    | Passou          |
| **Cenário 6**      | Logout bem-sucedido                                   | Passou          |
| **Cenário 7**      | Login com usuário em branco                           | Passou          |
| **Cenário 8**      | Login com senha vazia                                 | Passou          |
| **Cenário 9**      | Login com senha no formato certo mas minúscula        | Passou          |
| **Cenário 10**     | Login bem-sucedido após redefinição de senha          | **Falhou**      |



<br/>



 
<br/>

## Testes Candidatos à Automação

<br/>
### **Registro **

- **Cenário 1**: Registro bem-sucedido
  - **Justificativa**: Pode ser validado automatizando a criação de um novo usuário e verificando o retorno esperado.

- **Cenário 2**: Registro com e-mail já cadastrado
  - **Justificativa**: Testa a regra de unicidade de e-mail, verificando a mensagem de erro esperada.

- **Cenário 3**: Registro com senha fraca
  - **Justificativa**: Pode ser validado com uma entrada inválida e checando se o sistema bloqueia o registro. 

- **Cenário 4**: Registro com e-mail inválido 
  - **Justificativa**: Fácil de automatizar com diferentes formatos inválidos de e-mail.

- **Cenário 5**: Login bem-sucedido 
  - **Justificativa**: Verifica se um usuário válido consegue acessar o sistema corretamente.

- **Cenário 7**: Login com usuário em branco 
  - **Justificativa**: Entrada previsível, possível validar a resposta do sistema.

- **Cenário 8**: Login com senha vazia
  - **Justificativa**: Valida se o sistema bloqueia o login quando a senha não é informada.

- **Cenário 9**: Login com senha no formato certo mas minúscula
  - **Justificativa**: Semelhante ao cenário 7, fácil de validar a resposta.

- **Cenário 10**: Login após redefinição de senha
  - **Justificativa**: Pode ser automatizado simulando a redefinição e testando o login subsequente.



<br/>
 



## Tipos de Testes Funcional
<br/>

* Teste Web

<br/>




## Ambiente de Teste
<br/>

* Testes realizados em ambiente web ;
* Sistemas operacionais: Windows 10 home pro .


<br/>

## Ferramentas Utilizadas
<br/>

* Git 
* Github
* Xmind

  
<br/>

## Execução do Teste
<br/>

* Acessar ao repositorio https://github.com/danellaclaudioluiz/autenticator

* Ler o Readm e seguir os passos a passos

* criar um repositorio com nome neste formato exemplo : desafio_tecnico_qa_jose_henrique_souto
* ter o vs code instalado
* criar seu repositorio com nome formato exemplo acima
* pode começar a desenvolver seus testes
<br/>

## Atividades e estimativas :
<br/>
 
**Atividades de teste e estimativas**
<br/>

* Revisão de documentos, Lucas e 1 dia .

* Elaboração de cenários de teste, Lucas e 1 dia .
 

## Equipe :
<br/>
 

**Funções, atividades e responsabilidades**
<br/>

* Analista de Testes, Lucas , Criar cenários e casos de teste e executa-los .

  
   
<br/>
 

## Necessidades de contratação
<br/>

* Pra esse projeto não houve necessidade da contratação de nenhum serviço .
<br/>

## Necessidades de treinamento
<br/>

* N/A


<br/>
 

## Cronograma :
<br/>
 

* 21 de Fevereiro ~ 21 de Fevereiro : Criação do Mapa Mental;
* 21 de Fevereiro ~ 21 de Fevereiro : Criação do Plano de teste;
* 21 de Fevereiro ~ 21 de Fevereiro : Criação do Cenário de teste;
* 21 de Fevereiro ~ 21 de Fevereiro : Criação do Caso de teste;
* 21 de Fevereiro ~ 21 de Fevereiro : Execução do Caso de teste;
* 21 de Fevereiro ~ 21 de Fevereiro : Criação do Relatorio de teste;
* 21 de Fevereiro ~ 21 de Fevereiro : Criação do Reporter Bug;
* 21 de Fevereiro ~ 21 de Fevereiro : Revisão de todos os documentos feitos;
* 21 de Fevereiro ~ 21 de Fevereiro : Entrega do Projeto via email para a Empresa;
