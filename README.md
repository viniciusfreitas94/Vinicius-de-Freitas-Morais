# Vinicius-de-Freitas-Morais

## Visualizar o manifesto no Mirador

1. Instale as dependências necessárias para rodar um servidor HTTP simples (qualquer servidor estático funcionará; com Python já é suficiente).
2. No diretório raiz do projeto, execute um servidor local, por exemplo:
   ```bash
   python3 -m http.server 8000
   ```
3. Abra o navegador em `http://localhost:8000/viewer/mirador.html`.
4. O Mirador carregará automaticamente o manifesto em `manifests/jeanne-d-evreux.json`.

O arquivo `viewer/mirador.html` está configurado para apontar para o manifesto e inicializar o Mirador com a abertura do Livro de Horas de Jeanne d'Evreux.
