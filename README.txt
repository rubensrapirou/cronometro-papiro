Você Sargento — Plataforma de Estudos

Arquivos neste pacote:
- index.html  -> página web completa (login, cronômetro, constância, ranking)
- logo.png    -> (adicione sua logo transparente com este nome)
- README.txt  -> este arquivo

Como usar:
1) Extraia os arquivos deste ZIP.
2) Coloque sua imagem 'logo.png' na mesma pasta (substitua se quiser).
3) No Firebase Console, verifique que o Firestore está criado e em modo de teste.
4) Abra 'index.html' localmente para testar (ou faça deploy no GitHub Pages).
5) Usuarios podem criar conta com nome + senha. Dados de constância e ranking são salvos no Firestore.

Observações:
- Este frontend usa o Firestore para criar/ler/atualizar usuários. As regras de teste permitem leitura/escrita.
- Em produção, ajuste regras de segurança no Firestore.
