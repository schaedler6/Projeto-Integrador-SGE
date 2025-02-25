#  Atualização no Projeto: CI/CD Corrigido!

Olá, professores!

Acabei de corrigir e validar o **pipeline de CI/CD** no GitHub Actions. Agora, sempre que alguém fizer um **push** ou um **pull request** na branch \main\, os seguintes processos serão executados automaticamente:

 **Testes automatizados** (\pytest tests/\)  
 **Instalação das dependências**  
 **Deploy automático (simulado por enquanto)**  

Se os testes falharem, o GitHub Actions mostrará os **logs detalhados** com o erro. Para evitar problemas, confiram os logs sempre que um commit for rejeitado.

 **Onde ver os testes?**  
Acesse a aba **"Ações"** no repositório GitHub:  
 [https://github.com/schaedler6/Projeto-Integrador-SGE/actions](https://github.com/schaedler6/Projeto-Integrador-SGE/actions)  

 **Dica:** Antes de fazer push, rodem os testes localmente com \pytest tests/\ para evitar falhas.

 **Bora codar!**
