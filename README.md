# una-ihcux-lista05
Heurísticas de Usabilidade Aplicadas

5ª Heurística: Prevenção de Erros

Onde ocorre: Na própria escolha de usar a estrutura try-catch.

Como funciona: O código antecipa uma falha comum (o usuário digitar texto em um campo numérico). Em vez de permitir que o sistema sofra um crash e feche abruptamente, o bloco try atua como um escudo, capturando o problema antes que ele se torne um erro fatal para a experiência do usuário.

9ª Heurística: Ajudar os usuários a reconhecerem, diagnosticarem e recuperarem-se de erros

Onde ocorre: Dentro do bloco catch.

Como funciona: Se o erro acontecer, o sistema não exibe um código técnico indecifrável (como um Stack Trace de FormatException). Em vez disso, ele usa uma cor de alerta (vermelho) e entrega uma mensagem clara e construtiva, indicando o que deu errado e como consertar: "Por favor, digite apenas números inteiros (ex: 20)."

1ª Heurística: Visibilidade do Status do Sistema

Onde ocorre: Dentro do bloco try (linha de sucesso).

Como funciona: O sistema não fica em silêncio após o usuário acertar. Ele fornece um feedback imediato e claro confirmando a ação: "Cadastro confirmado. Você tem X anos." Isso garante ao usuário que a entrada foi aceita e processada corretamente.
