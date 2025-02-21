# Metricas de Teste
<br/>


| **ID do Cenário** | **Descrição**                                          | **Status**      | **Resultado Esperado**                                      | **Resultado Obtido**         | **Status do Teste** |
|-------------------|--------------------------------------------------------|-----------------|-------------------------------------------------------------|-----------------------------|----------------------|
| **Cenário 1**      | Registro bem-sucedido                                 | Passou          | O sistema deve registrar o usuário com sucesso.             | Registro realizado corretamente. | **Passou**           |
| **Cenário 2**      | Registro com e-mail já cadastrado                     | Passou          | O sistema deve impedir o cadastro com e-mail duplicado.     | Impedido cadastro duplicado.  | **Passou**           |
| **Cenário 3**      | Registro com senha fraca                              | Passou          | O sistema deve impedir o registro com senha fraca.          | Impedido cadastro com senha fraca. | **Passou**           |
| **Cenário 4**      | Registro com e-mail inválido                          | Passou          | O sistema deve impedir o cadastro com e-mail inválido.      | Impedido cadastro com e-mail inválido. | **Passou**           |
| **Cenário 5**      | Login bem-sucedido                                    | Passou          | O sistema deve permitir o login com credenciais corretas.  | Login realizado corretamente. | **Passou**           |
| **Cenário 6**      | Logout bem-sucedido                                   | Passou          | O sistema deve permitir o logout com sucesso.               | Logout realizado corretamente. | **Passou**           |
| **Cenário 7**      | Login com usuário em branco                           | Passou          | O sistema deve impedir login com usuário em branco.         | Login impedido.              | **Passou**           |
| **Cenário 8**      | Login com senha vazia                                 | Passou          | O sistema deve impedir login com senha vazia.               | Login impedido.              | **Passou**           |
| **Cenário 9**      | Login com senha no formato certo mas minúscula        | Passou          | O sistema deve permitir login com senha no formato correto, mesmo minúscula. | Login realizado corretamente. | **Passou**           |
| **Cenário 10**     | Login bem-sucedido após redefinição de senha          | **Falhou**      | O sistema deve permitir login com senha redefinida corretamente. | Login falhou após redefinição. | **Falhou**           |

### Total de Cenários: 10
- **Passaram:** 9
- **Falharam:** 1
- **Taxa de Sucesso:** 90%
