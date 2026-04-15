# atividade-5
algoritmo "AnaliseDividendYield"

var
   dy : real

   inicio
      // Entrada do valor
         Escreva("Digite o Dividend Yield (DY) da ação (%): ")
            Leia(dy)

               // Verificação das condições
                  Se dy > 6 Entao
                        EscrevaL("Estratégia de Renda Passiva OK")
                           Senao
                                 Se (dy >= 4) E (dy <= 6) Entao
                                          EscrevaL("Atenção: Rendimento Médio")
                                                Senao
                                                         EscrevaL("Rendimento Baixo")
                                                               FimSe
                                                                  FimSe
                                                                  fimalgoritmo
