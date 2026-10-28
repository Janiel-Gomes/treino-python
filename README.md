# Treino de Python

Site estático com 20 exercícios de Python básico. O código roda no navegador (interpretador Skulpt) e cada exercício tem correção automática. O progresso fica salvo no navegador de quem usa.

## Estrutura

- `index.html`: o site inteiro (HTML, CSS e JavaScript em um arquivo só)

Não tem build nem dependências para instalar. As bibliotecas (Skulpt) e as fontes são carregadas de CDN, então é preciso internet para abrir.

## Testar no computador

Abra o `index.html` no navegador. Se preferir um servidor local:

```
python3 -m http.server 8000
```

e acesse http://localhost:8000.

## Publicar na Vercel

1. Crie um repositório no GitHub e envie estes arquivos.
2. Na Vercel, clique em **Add New... > Project** e escolha o repositório.
3. Em **Framework Preset**, deixe **Other**. Não precisa de comando de build nem de pasta de saída.
4. Clique em **Deploy**.
