![Lucree](https://lucreestatic.s3.us-east-2.amazonaws.com/dashboard/assets/img/brand/logo-lucree-horizontal.png)

# A aplicação flask mais simples do mundo

## Rodando

Basta executar `python app.py`. A porta está definida no código. A variável de ambiente `LUCREE_PASSWD` é necessária para definir o token da aplicação. 

## Chamando a aplicação

```bash
curl -H "Authorization: Token VALOR_DA_ENVVAR_LUCREE_PASSWD" http://localhost/
```

**Lembre-se que você é livre para modificar essa aplicação.**
