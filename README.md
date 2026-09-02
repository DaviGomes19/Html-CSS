Do que se trata

É a página inicial (estrutura HTML, sem CSS) de um site fictício para uma academia chamada "Star Academy". A página apresenta a academia, suas modalidades de treino (Musculação, Funcional, Yoga) e um formulário de inscrição para aula experimental.

Como é estruturado

O documento segue a estrutura básica do HTML5 (<!DOCTYPE html>, <html>, <head>, <body>), organizado em 4 blocos principais:

Cabeçalho – título e menu de navegação
Seção "Sobre" – texto de apresentação da academia
Seção "Planos e Modalidades" – três cartões (<article>) com as modalidades oferecidas
Seção "Inscrição" – formulário completo para o visitante se inscrever

Observações técnicas
O HTML é totalmente semântico na maior parte (<nav>, <main>, <section>, <article>), boa prática de acessibilidade e SEO.
Os inputs usam atributos de validação nativa (required, type="email", min/max), reduzindo necessidade de JavaScript para validação básica.
O uso de <br><br> para espaçamento é uma prática não recomendada — o ideal seria usar CSS (margin, gap) para isso.






























