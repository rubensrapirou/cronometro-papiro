
Você Sargento — v5 (com Firebase)

Arquivos:
- index.html (app completo)
- README.txt (este arquivo)

Instruções rápidas:
1) Substitua/adicione sua logo transparente como 'logo.png' na raiz do repositório.
2) Verifique Firestore criado em modo teste no seu projeto 'voce-sargento'.
3) Faça upload de index.html and logo.png para o repositório do GitHub Pages.
4) Abra a URL do Pages and teste login (usuário de exemplo 'futurosargento' / senha '1234').

Observações:
- O código usa Firestore para usuários (coleção 'users').
- Não utiliza Firebase Auth; senhas são hasheadas via SHA-256 e gravadas no Firestore.
- Para produção, ajuste regras do Firestore para autenticar adequadamente.
