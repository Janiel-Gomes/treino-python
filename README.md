# Treino de Python

Site estático com 20 exercícios de Python básico. O código roda no navegador com o interpretador Skulpt e cada exercício tem correção automática. O progresso fica salvo no navegador de quem usa.

## Estrutura

- `index.html`: o site (HTML, CSS e JavaScript)
- `vendor/`: arquivos do interpretador Skulpt 1.2.0 (`skulpt.min.js` e `skulpt-stdlib.js`), já incluídos no projeto

Não tem build nem dependências para instalar. Só as fontes vêm da internet (Google Fonts); sem elas o site usa fontes do sistema.

## Testar no computador

```
python3 -m http.server 8000
```

e acesse http://localhost:8000.

## Publicar na Vercel

1. Crie um repositório no GitHub e envie todos os arquivos, incluindo a pasta `vendor`.
2. Na Vercel, clique em **Add New... > Project** e escolha o repositório.
3. Em **Framework Preset**, deixe **Other**. Não precisa de comando de build.
4. Clique em **Deploy**.
