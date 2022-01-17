"condition-layout.product": faz verificações condicionais para a pagina e adiciona componentes caso a comparação retorna true.
    "conditions": Propiedade de configurações de condições
        "subject":  é o dado que vai ser usado para fins de comparação, no nosso caso usaremos productId, na documentação é possível ver todas as opções disponíveis;
        "verb": é o método comparativo, usaremos o is para validar se o productId é de um produto específico, mas poderíamos usar: is, is-not, contains ou does-not-contain.
        "object": é o valor com que queremos comparar, no nosso caso iremoms usar productId 20

!!! Ao passar as paginas notara que apenas as paginas que possui o id 2 apresentara a imagen.