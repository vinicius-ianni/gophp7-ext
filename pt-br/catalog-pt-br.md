##Catalogo de extensões:

Esta é a pagina mamute de nossa wiki: <a href='https://github.com/gophp7/gophp7-ext/wiki/extensions-catalog'>https://github.com/gophp7/gophp7-ext/wiki/extensions-catalog</a>. 

Ela se divide em seções pelo tipo da extensão:
  
  Core 
pecl.php.net 
pecl (not php.net) 
Outras extensões

###Como você pode ajudar

Nós precisamos listar aqui tanto as extensões quanto as informações que encontrarmos sobre elas. Cada extensão precisa de uma coluna na tabela com as seguintes (marioria sim/não) informações:
  
  Name (*nome)
Homepage/location (*homepage/endereço)
Has maintainers  (*possui mantenedor)
Has tests  (*possui testes)
Has docs (*possui documentação)
Works on PHP5 (newest PHP 5) (*funciona no PHP5 (**ultima versão PHP5))
Works on PHP7  (*funciona no PHP7)
Is good on PHP 7 (*É bom no PHP7)
Details - (*Detalhes) link para uma nova pagina wiki e escrever mais sobre o estado do projeto e o que precisa ser feito antes de responder tudo com “sim” 

Você pode editar nosso modelo de linha (não precisa estar alinhado) para você mesmo criar uma nova entrada:
  
  | Homepage/location | Has maintainers | Has tests | Has docs | Works on PHP5 | Works on PHP7 | Is good on PHP 7 | Details | 
  
  Por favor, preencha com toda informação que você puder.... e onde houver lacunas, adivinhe de quem será o trabalho de preenche-las ?

###Encontrando extensões:

Você está usando uma extensão PHP ? Veja se ela já está na nossa lista, e caso não esteja, adicione-a !
  
  ###Entrando em contato com os mantenedores:
  
  Por favor, entre em contato com os mantenedores e verifique se eles ainda estão ativos – Os detalhes de contato devem ir para a página de detalhes da extensão. Se não tiver mantenedores, ou um único mantenedor, veja se você pode encontrar alguém que se envolva com a extensão. Se você não tiver uma resposta, sinta-se livre para forkar a extensão e continuar com ela.

###Possui testes

Rode os testes. Se adicionar mais testes, ganha pontos extras.


De uma olhada em <a href='http://qa.php.net/>http://qa.php.net</a>  e aprenda como escrever testes .phpt (previa: eles são realmente fáceis) 

###Possui documentação

Onde está a documentação ? Alguns recursos para você se precisar escrever ou atualizar os documentos para uma extensão 

Dê uma olhada em <a href='http://doc.php.net/'>http://doc.php.net/</a> para aprender como escrever documentação para o php.net
Dê uma olhada em <a href='http://readthedocs.org '>http://readthedocs.org</a> para aprender como criar uma documentação offsite

###Funciona no PHP5 

Tente <a href='http://www.lornajane.net/posts/2014/compiling-php-extensions '>http://www.lornajane.net/posts/2014/compiling-php-extensions</a> como ponto de partida (que provavelmente será forkado para uma pagina neste site para que possamos melhorar e atualizar-lo).

###Funciona no PHP7 

Faze-lo no PHP7 (enquanto ainda está sendo feito) este é provavelmente a parte mais dificil, parte das pessoas querem aprender extensões ou sabem como C funciona – isto inclui mudanças de pensamento sobre melhores práticas, coisas para prestarmos atenção, como migrar vai ajudar mais tarde as pessoas a ganherem velocidade.

###É bom no PHP

Fazer isso funcionar DIREITO no PHP7 – isso é mais do que apenas códigos em C... se eles não tiverem testes, adicione os testes, se ele não tem documentação, crie os documentos, se suas apis foram projetadas 10 anos atrás e usar seus recursos irá feri-lo se você toca-los – refaça as apis, crie com travis e appveyor (windows ci) para que sejam continamente testados, corrigir os erros pendentes, adicionar novos recursos – mantenha as extensões vivas e bem.

###Detalhes

Página adicional com mais informações, quaisquer outras questões, etc...