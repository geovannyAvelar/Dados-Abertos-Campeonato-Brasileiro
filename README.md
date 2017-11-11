# Dados abertos Campeonato Brasileiro
Dados abertos das partidas do Campeonato Brasileiro de Futebol da Série A desde o início da era dos pontos corridos, em 2003. Arquivos no formato JSON (Javascript Object Notation). Retirados do repositório do openfootball, acesso via https://github.com/openfootball/br-brazil.

O JSON segue a seguinte estrutura:

```
{
  "partidas": [{
      "mandante": "Guarani",
      "visitante": "Vasco",
      "data_partida": "29/03/2003",
      "hora_partida": "16h00",
      "placar_mandante": 4,
      "placar_visitante": 2,
      "resultado": "vitoria_mandante",
      "estadio": "Brinco de Ouro", 
      "pontuacao_geral_mandante": { 
                "jogos_casa": 1, 
                "total_gols_sofridos": 2, 
                "empates_fora_casa": 0,
                "pontos_casa": 3,
                "total_vitorias": 1,
                "gols_casa": 4,
                "gols_fora_casa": 0,
                "jogos_fora_casa": 0,
                "total_pontos": 3,
                "vitorias_casa": 1,
                "derrotas_casa": 0,
                "derrotas_fora_casa": 0,
                "total_jogos": 1,
                "vitorias_fora_casa": 0,
                "total_derrotas": 0,
                "total_gols_marcados": 4,
                "empates_casa": 0,
                "total_empates": 0,
                "pontos_fora_casa": 0 
       },
       "pontuacao_geral_visitante": {
                "jogos_casa": 0,
                "total_gols_sofridos": 4,
                "empates_fora_casa": 0,
                "pontos_casa": 0,
                "total_vitorias": 0,
                "gols_casa": 0,
                "gols_fora_casa": 2,
                "jogos_fora_casa": 1,
                "total_pontos": 0,
                "vitorias_casa": 0,
                "derrotas_casa": 0,
                "derrotas_fora_casa": 1,
                "total_jogos": 1,
                "vitorias_fora_casa": 0,
                "total_derrotas": 1,
                "total_gols_marcados": 2,
                "empates_casa": 0,
                "total_empates": 0,
                "pontos_fora_casa": 0 
         }
       }
     ],
  "numero": 1
}
```

Sendo que a lista "partidas" pode conter entre dez e doze partidas, dependendo do ano. Os campos "pontuacao_geral_mandante" e "pontuacao_geral_visitante" guardam os dados da tabela do campeonato na data da partida. Os campos "hora_partida" e "estadio" podem constar vazios, pois tais dados nem sempre estão disponíveis.

# Licença
Esse projeto está sob os termos da The MIT License (MIT).
