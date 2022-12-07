# shopify-price-instalments
Code to add "In up to 12x" below the product price.

br - Código para adicionar "Em até 12x sem juros", abaixo do preço do produto em toda loja.

code
      <span>em até <span>12x</span> de <span> 
{{ price | divided_by: 11.93 | times: 1.1979 | money }}</span>
