# FlowPay Documentation

Use este kit de documentação para ter sua documentação implantada e pronta para personalização.

Este kit de documentação do FlowPay contém exemplos com

- Guide pages
- Navigation
- Customizations
- API reference pages
- Use of popular components

**[Siga o guia de início rápido](/quickstart)**

## Desenvolvimento

Instale a [CLI do Mintlify](https://www.npmjs.com/package/mint) para visualizar suas alterações de documentação localmente. Para instalar, use o seguinte comando:

```
npm i -g mint
```

Execute o seguinte comando na raiz da sua documentação, onde seu arquivo `docs.json` está localizado:

```
mint dev
```

Visualize sua prévia local em `http://localhost:3000`.

## Publicando alterações

Instale o aplicativo GitHub a partir do seu dashboard para propagar alterações do seu repositório para a implantação. As alterações são implantadas em produção automaticamente após o push para a branch padrão.

## Precisa de ajuda?

### Solução de problemas

- Se seu ambiente de desenvolvimento não estiver funcionando: Execute `mint update` para garantir que você tenha a versão mais recente da CLI.
- Se uma página carregar como 404: Certifique-se de estar executando em uma pasta com um `docs.json` válido.

### Recursos
- [Documentação do Mintlify](https://mintlify.com/docs)
