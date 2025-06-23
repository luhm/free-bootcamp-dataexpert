Dimensional data modelling





dimension - atributos que podem ou não ajudar a identificar especificamente uma entidade





alguns ajudam a identificar uma entidade - cpf, id de uma compra



2 tipos:





slowly-chage





algumas coisas que mudam de tempo em tempo



tipo de comida que gosta



é type-dependent



fixed





não muda



data de nascimento



são mais fáceis de modelar



OLTP





online transaction processing



volume baixo de queries



mais rapido no geral pois é bem filtrado e focado



OLAP





online analytical processing



volume alto e facilita que essas queries sejam rapidas



é o mais comum



Master data





fica entre os outros dois



deduplicado



completo



se não usar a forma correta de modelagem, pode fazer um app ser mais lento



OLTP e OLAP são um continuum





dados de transacional que vai pra uma Master data e depois pra OLAP e aí conseguir ver as metricas



OLAP é onde conseguimos usar where's em uma querie





Saber quem é seu cliente





quem precisa desse dado/informação?
