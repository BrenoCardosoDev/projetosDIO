# Validando a Força de Senhas no IAM

# Desafio
Você está trabalhando para uma empresa que utiliza extensivamente os serviços da AWS, e após algumas análises a equipe de segurança identificou que algumas senhas dos usuários no IAM são fracas e podem representar um risco à segurança dos dados da empresa. 
Para resolver esse problema, foi solicitado que você desenvolva um programa capaz de analisar as senhas dos usuários e fornecer uma validação de força com base em critérios predefinidos.

Requisitos de segurança para a senha:
1.	A senha deve ter no mínimo 8 caracteres.
2.	A senha deve conter pelo menos uma letra maiúscula (A-Z).
3.	A senha deve conter pelo menos uma letra minúscula (a-z).
4.	A senha deve conter pelo menos um número (0-9).
5.	A senha deve conter pelo menos um caractere especial, como !, @, #, $, %, etc.

Saiba mais sobre o Regex em: [Java Regular Expressions](https://www.w3schools.com/java/java_regex.asp)

# Entrada
A entrada será uma única string representando a senha que precisa ser validada.

# Saída
Seu programa deve retornar uma mensagem indicando se a senha fornecida pelo usuário atende aos requisitos de segurança ou não, juntamente com um feedback explicativo sobre os critérios considerados.

| Entrada	| Saída |
| - | - |
| 0101	| Sua senha e muito curta. Recomenda-se no minimo 8 caracteres. |
| 030609saturno*	| Sua senha atende aos requisitos de seguranca. Parabens! |
| 010203 | Jupiter	Sua senha nao atende aos requisitos de seguranca. |
