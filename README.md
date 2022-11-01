## Template

### O que é um template no stack spot?

O template é aquele modelo de código usado todas as vezes ao precisar um novo projeto, podendo ser uma api já contendo todas configurações necessárias e padrões de código, ou um worker já configurado com um provider de mensageria.

### Como usar um template?

Para criar um template, basta executar o comando abaixo dentro da pasta da stack.

```csharp
stk create template {nome_template}
```

Ou também você pode usar um template compartilhado de uma organização usando o argumento --remote, com o comando abaixo.

```csharp
stk create template --remote {url_do_template}
```

📝**Note:** O repositório remoto deve ser git.

# Utilizando um template

```csharp
stk create app {nome_app} -p {path_template} 
```

Ou também você pode usar um template que está em um repositório git usando o argumento --remote, com o comando abaixo.

```csharp
stk create app {nome_app} -remote {url_template} 
```

📝**Note:** O repositório remoto deve ser git.
